# http-response-checker

This is a bash script that verifies the validity of URL responses, specifically identifying responses that are not "000." It can be employed to determine whether a domain can lead to a valid URL or not.

## Usage

Change file permission to executable
```
chmod +x http-response-checker.sh
```
Execute the file
```
./http-response-checker.sh <domains> <output-file>
```

## Result
```
HTTP Response Code for http://company-a.com/: 200
HTTP Response Code for http://company-b.com.com: 200
```
