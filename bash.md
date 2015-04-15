# redirect stdout and stderr to tee

command > >(tee stdout.log) 2> >(tee stderr.log >&2)
