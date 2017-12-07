#gulp基本概念
1、是task任务管理 default（默认任务）
2、src dest
3、src 是开发目录，将开发目录里的文件，经过处理，会有：转译es6,压缩，合并。
最后将其目标文件放至到dist线上目录
4、babel转译任务集成到gulp中
yarn add --dev gulp-babel babel-core babel-preset-env
5、压缩css gulp-clean-css