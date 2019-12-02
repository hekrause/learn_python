# Useful conda commands

#### Create an environment from a spec-file.txt
<pre>conda create --name <b>myenv</b> --file <b>spec-file.txt</b></pre> PS: replace <b>myenv</b> and <b>spec-file.txt</b> with your values.

#### Install packages from a spec-file.txt
<pre>conda install --name <b>myenv</b> --file <b>spec-file.txt</b></pre> PS: replace <b>myenv</b> and <b>spec-file.txt</b> with your values.

#### Create a spec-file.txt from your current environment
<pre>conda list -name <b>myenv </b>--explicit > <b>spec-file.txt</b></pre> PS: replace <b>myenv</b> and <b>spec-file.txt</b> with your values.

#### Activate/Enter an environment:
<pre>conda activate <b>myenv</b></pre> PS: replace <b>myenv</b> with your environment name.
	
#### Deactivate/Leave an environment
<pre>conda deactivate</pre>