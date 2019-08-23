# SUNCGUnityViewer
Tool to view the SUNCG Dataset in Unity http://suncg.cs.princeton.edu/

TIL: https://futurism.com/tech-suing-facebook-princeton-data
So you can't get the dataset anymore! Thank you to the folks who sent me kind messages about how the package helped them <3 

## To Use:

        House h = House.LoadFromJson("<PATH_TO_HOUSES>/house.json");
        Loader l = new Loader();
        l.HouseToScene(h);
        
You must also set the root path to the SUNCG Data set in Config.cs
