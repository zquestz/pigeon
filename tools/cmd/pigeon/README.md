# Pigeon App

The `pigeon` command submits images to Google Cloud Vision API.

## Prerequisite

You need to export a service account json file to `GOOGLE_APPLICATION_CREDENTIALS` variable.

```
$ export GOOGLE_APPLICATION_CREDENTIALS=/path/to/service_account.json
```


## Installation

Type the following line to install `pigeon`.

```shell
$ go get github.com/zquestz/pigeon/tools/cmd/pigeon
```

Make sure that `pigeon` was installed correctly:

```shell
$ pigeon -h
```


## Run

```
$ pigeon assets/lenna.jpg
$ pigeon -face gs://bucket_name/lenna.jpg
```

## Example

![pigeon-cmd](https://raw.githubusercontent.com/zquestz/pigeon/master/assets/pigeon-cmd.gif)


## License

[The MIT License (MIT)](http://zquestz.mit-license.org/)


## Author

Shintaro Kaneko <kaneshin0120@gmail.com>

