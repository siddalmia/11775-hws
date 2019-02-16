Full pipeline is given in the shell script run.pipeline.sh.
You can pass pass arguments to this bash script defining which one of the steps you want to perform.
This helps you to avoid rewriting the bash script whenever there are
intermediate steps that you don't want to repeat.

execute: bash run.pipeline.sh -p true -f true -m true -k true -y filepath
