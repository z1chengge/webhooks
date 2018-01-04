# webhooks
curl 'https://oapi.dingtalk.com/robot/send?access_token=b4faa10c068f3c7b84b8640563a88d6cde713da783def013451872c5d0b3407d' \
   -H 'Content-Type: application/json' \
   -d '
  {"msgtype": "text", 
    "text": {
        "content": "我就是我, 是不一样的烟火"
     }
  }'
