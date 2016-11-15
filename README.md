# ApplicationLifecycleManager
A very handy way to manage lifecycle of application, one can check wether application is in background or in foreground.

Add line of code below in Application-> onCreate()

//Register Acitivity lifecycle callbacks
registerActivityLifecycleCallbacks(new ApplicationLifecycleManager());


Check application visibility status any where:

//Check is application visibility
ApplicationLifecycleManager.isAppVisible()
