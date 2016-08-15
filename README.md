# Sniffex
A Packet sniffing application written in C

#Appfile
The file "sniffex.yaml" is an example appfile required to launch this application using Solum in OpenStack.
The rumprun lp must be created in solum for the app to be deployed and run correctly.

#Params
The "params.yaml" file is used by Solum to pass user defined environment variables to the application environment. It is used in the case of unikernels to instruct solum of the type of unikernel our appplication is meant to run on i.e. "kernel_type" and also any kernel cmdline args or application args that the unikernel may need.

TODO: show how unikernels are deployed without solum?!

#Requirements
Dependencies of this application are installed using app-get so requirements are listed in a space-delimited list.
