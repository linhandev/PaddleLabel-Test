# pp-label-test

Test backend API
1. install [insomnia](https://github.com/Kong/insomnia)
2. install [path param plugin](https://insomnia.rest/plugins/insomnia-plugin-path-parameters)
3. import insomnia.yaml and goto debug on the top.

Test project import / export:
1. change pplabel.config.task_test_basedir to where testing data is
2. python test_task.py

each import / export process is defined under pplabel.task.[task_name] (eg: classification/detection/segmentation)

The testing data I use:

https://pan.baidu.com/s/1JjSY7dQLQhD2ynK9Co6zyw ai80
