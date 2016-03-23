# GoPiGo 满地乱跑的树莓派机器人

以下全部为英文文档

1. [组装GoPiGo](http://www.dexterindustries.com/GoPiGo/getting-started-with-your-gopigo-raspberry-pi-robot-kit-2/1-assemble-the-gopigo-2/assemble-gopigo-raspberry-pi-robot/1-assemble-the-gopigo2/)
2. [Mac下往SD卡里安装树莓派操作系统Raspbian](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md)

    更新并自动设置时间
    
    ```
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install ntpdate
    ```
    
3. [使用网线和路由器，在没有显示器的情况下配置树莓派](http://jacobjthomas.com/how-to-raspberry-pi-headless-setup-on-first-boot/)
4. [使用wpa_cli添加无线网络](http://raspberrypihq.com/how-to-add-wifi-to-the-raspberry-pi/)

    ```
    add_network
    set_network <nid> ssid "<your ssid>"
    set_network <nid> psk "<your psk>"
    enalbe_network <nid>
    save_config
    ```
    
5. [安装GoPiGo](http://www.dexterindustries.com/GoPiGo/getting-started-with-your-gopigo-raspberry-pi-robot-kit-2/sdcard-2/)
6. [动起来！树莓派机器人~](http://www.dexterindustries.com/GoPiGo/projects/python-examples-for-the-raspberry-pi/basic-robot-control-with-the-raspberry-pi-gopigo/)