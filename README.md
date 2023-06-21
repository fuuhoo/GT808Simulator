# GT808Simulator
部标808终端模拟器

还在完善中...

终端注册0x0100

终端鉴权0x0102

终端心跳0x0002

位置和报警0x0200



文本编辑器打开GT808Simulator.exe.config文件修改remoteServerPort值为自己的服务器地址。
或者通过设置-服务器设置进行修改。
循环发送只支持200
  <appSettings>
    <!--服务器IP和端口(10.1.97.12:32195)-->
    <add key="remoteServerPort" value="10.1.97.12:32195" />
  </appSettings>
