# docker-resume-json-editor
A Docker Container for resume-json online editor, I fork the online editor from [erming/resume-editor](https://github.com/erming/resume-editor) and add some functions into that.

# Feature
- Download file supports html and json formats. you can download the json format and use **resume-cli** to handle that json.

# Usage

The container runs a www-server on port 8001 and you should use **-p** to forward to port to **8001**.

## Example

```
docker pull hwchiu/docker-resume-json-editor
docker run --name resume -p 80:8001 hwchiu/docker-resume-json-editor
```

After that, open your browser and type the **$ip:80** in the serach bar and you can editor the resume now.
