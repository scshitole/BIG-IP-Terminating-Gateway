# Lets Enable Envoy Proxy for microapp1 part2 


1. Once login to the microapp1 client

2. Run the commands below on the microapp1 vm: ```curl -L https://getenvoy.io/cli | sudo bash -s -- -b /usr/local/bin```

3. Get Envoy binary ```getenvoy run standard:1.13.0 -- --version```

4. Copy the binary to usr/local/bin ```sudo cp ~/.getenvoy/builds/standard/1.13.0/linux_glibc/bin/envoy /usr/local/bin/```

5. Check the Envoy version ```envoy --version```

 ![alt text](../../../../../../../images/copyenvoy.png)

6. Run the Envoy Sidecar command for microapp1 ```consul connect envoy -sidecar-for microapp1```

 ![alt text](../../../../../../../images/runsidecar.png)


[GoTo Next Exercise-8](8-ex)

[GoBack](../README.md)
