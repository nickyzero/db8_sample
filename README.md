# webOS DB8 Sample

# Summary
This is a sample project for using DB8 of webOS OSE. This sample shows how to create DB8 kind, how to put items to created kind, how to get items from kind, and how to delete kind.

# Tutorial
### 0. Clone the repository
``` 
$ git clone https://github.com/nickyzero/db8_sample.git
$ cd db8_sample
```

Before packaging, you have to install CLI from [webOS OSE Developer Site](http://webosose.org) and set up environment.

### 1. Make a package
```
$ ares-package .
```
when pacakging finished, you can see package file that have ''.ipk'' file extension. 

### 2. Install a package to device
```
$ ares-install -d <device name> <package name>
```

### 3. Launch application using CLI
```
$ ares-launch -d <device name> <app id>
```
or 

You can launch your application on the device.

# How to test
### 1. Create Kind
Press ''Create(putKind)'' button to create kind.

### 2. Put items to Kind
Press ''put items(put)'' button to put items to kind.

### 3. Find items from kind
Press ''Find items By Kind(find)'' button to find items from kind.

### 4. Delete kind
Press ''Delete Kind(delKind)'' button to delete kind.
