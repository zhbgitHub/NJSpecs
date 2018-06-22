
# 组件仓库
#### 组件项目[swiftProject](https://github.com/NJHu/swiftProject.git)

- 1, 添加仓库到本地

```bash

pod repo add NJSpecs https://github.com/NJHu/NJSpecs.git

```


- 2, Podfile 引用source

```
source 'https://github.com/NJHu/NJSpecs.git' # NJ 私有源

platform :ios, '10.3'
use_frameworks!
target '***' do

pod 'NJKit'

end

```

- 3, 组件列表

  - [NJKit](https://github.com/NJHu/NJKit.git)
  - [DYTrends](https://github.com/NJHu/DYTrends.git)
  - [NJMediator](https://github.com/NJHu/NJMediator.git)
  - [NJMediator_DYTrends](https://github.com/NJHu/NJMediator_DYTrends.git)
  - [DYLiveShow](https://github.com/NJHu/DYLiveShow.git)
  - [NJMediator_DYLiveShow](https://github.com/NJHu/NJMediator_DYLiveShow.git)
  - [NJDYSearchBarView](https://github.com/NJHu/NJDYSearchBarView.git)
  - [NJIJKPlayer](https://github.com/NJHu/NJIJKPlayer.git)
  - [NJDYPlayer](https://github.com/NJHu/NJDYPlayer.git)
