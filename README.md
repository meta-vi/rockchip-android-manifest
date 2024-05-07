# rockchip-android-manifest
## How to build for VisAI-Edge
```
repo init -u https://github.com/meta-vi/rockchip-android-manifest.git -b android11-rockchip -m tinker_board_2-android11-vis-ai-2.0.15.xml
repo sync -c -j8
./docker_builder/docker-builder-run.sh
```
