#  Wrong Spooky Season - forensics

## Description
*"I told them it was too soon and in the wrong season to deploy such a website, but they assured me that theming it properly would be enough to stop the ghosts from haunting us. I was wrong." Now there is an internal breach in the `Spooky Network` and you need to find out what happened. Analyze the the network traffic and find how the scary ghosts got in and what they did.*

## Attached files
- capture.pcap

![Screenshot_7](https://user-images.githubusercontent.com/111431985/197845413-c4a03e8d-39e7-4e5f-946e-6cd6531f1656.png)

## Flag
```HTB{j4v4_5pr1ng_just_b3c4m3_j4v4_sp00ky!!}```

## Solution
This was forensics challenge. First I analyzed pcap file with tcpick

![Screenshot_8](https://user-images.githubusercontent.com/111431985/197845597-4472b6aa-670d-4e77-8ea0-89c3d7bb821a.png)

This returned very familiar string - base64 in reversed order. From there I only had to reverse the string and decode it.

![Screenshot_9](https://user-images.githubusercontent.com/111431985/197845767-a8e79fa4-3a68-4a26-9d83-e620e4f5e9fe.png)
![Screenshot_10](https://user-images.githubusercontent.com/111431985/197845779-9f1c12bd-99e8-472d-8b27-b20ef16f76a4.png)
