# tf-open-pose-experiment
Tensorflow Open Pose example using pipenv

### Install Tensorflow
`pipenv install --verbose https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.9.0-py3-none-any.whl`


### Install Dependency from Git repo
pipenv install git+https://git@github.com/ildoonet/tf-pose-estimation#egg=tf-pose

### Triubleshoot :
sh: no matches found: git+git@github.com:ildoonet/tf-pose-estimation.git#egg=tf-pose
`unsetopt nomatch`
Refer: https://github.com/robbyrussell/oh-my-zsh/issues/31

### Install OpenCV 
`pipenv install opencv-python`