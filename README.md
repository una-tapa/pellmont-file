# Hello
Hello, Pellmont. Sorry it took me a while. 

## Trace 
I uploaded `bootstrap.properties` that has the trace option we would like you to provide us.
Then our dev will review and hopefully approve the merge! 
- Place it under `\wlp\usr\servers\{server_name}\bootstrap.properties`. 
- Run the scenario
- Kindly provide us trace under `\wlp\usr\servers\{server_name}\logs`

## Jar 
I am not sure if you would like to try.. but just thought to upload. 
- I uploaded `com.ibm.ws.webcontainer.security_1_0.48.jar` that has a switch to not to add the hashtable. 
- The code change can be checked in `WebProviderAuthenticatorHelper.jad`, which is not elegant code.. 
- To turn on/off, please see `jvm.options`. Please place it under the same directory where `sever.xml` and `bootstrap.properties` are.  
