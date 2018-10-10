Execute artisan commands inside your docker container through a GUI
Windows only

# Instructions
1. edit App.config to set the path key to math the Laravel path in your machine.
```
<?xml version="1.0" encoding="utf-8" ?>
<configuration>
    <startup> 
        <supportedRuntime version="v4.0" sku=".NETFramework,Version=v4.6.1" />
    </startup>
  <appSettings>
    <add key="path" value="/home/medpets/WWW/laravel/"/>
  </appSettings>
</configuration>
```
2. Select the container running Laravel (artisan) in the first combobox.
3. Select the command you wish to execute in the second combobox. You should see the description of the command appear at the top of the window.
4. Optionally add additional arguments in the textbox.
5. Press "RUN" and enjoy.

![Screenshot](https://i.imgur.com/VGx6cYJ.png)