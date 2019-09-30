# air-adb

You can use this script to set up adb network debugging on the phone with the terminal application and root.

Terminal application recommend [Termux](https://termux.com/)

## How to use?

If you are working on an SD card:

### Install

```shell
wget -O air-adb https://raw.githubusercontent.com/moeshin/air-adb/master/air-adb
```

### Run

```shell
sh air-adb
```

Else we can:

### Install

```shell
wget -O air-adb https://raw.githubusercontent.com/moeshin/air-adb/master/air-adb && chmod +x air-adb
```

### Run

```
./air-adb
```

## Usage

```
./air-adb -?|-h|--help		Get help
./air-adb [port]			Start adb over network
./air-adb stop				Stop adb over network
./air-adb status 			Get Status
```



