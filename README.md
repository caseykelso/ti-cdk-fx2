# ti-cdk-fx2
TI CDK FX2 Firmware - top level project

# Setup Environment (Ubuntu 17.04)
```bash
sudo apt-get install build-essential repo ant git libboost-graph-dev
```

# Get the source
```bash
repo init -m fx2cdk.xml -u git://github.com/caseykelso/ti-cdk-fx2.git
repo sync
```

# Build Tool-chain
```bash
ant bootstrap
```

# Build FX2 Firmware
```bash
ant build
```

