# Metrics-collector 
Metrics collector collects metrics from multiple urls and exposes them on a socket
The software can for instance be used to collect metrics from multiple servers/containers
running Almond.

# Compile
g++ main.cpp util.cpp logger.cpp -lcurl -ljsoncpp -o metrics-collector

# Run
metrics-collector <port>
