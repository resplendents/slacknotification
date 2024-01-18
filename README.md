# slackNotification
구글 시트의 Status 열 현황이 Open - In Progress - Completed 변동 시 슬랙 알림을 보냅니다. </br>
slack api 권한 및 install 과정의 **코드**는 따로 문의주시면 전달드리겠습니다. 

# slack api 
1. Slack api > Features > Incoming Webhooks - Add New Webhook to Workspace
2. 메시지 전송할 채널 선택, Allow
3. Webhook URL copy 

# google sheet (install)
1. PO sheet > 확장 프로그램 > Apps Script
2. **코드** 붙여넣기
3. save 
4. 실행할 함수 선택 > create trigger 
5. 실행

# google sheet (uninstall) 
1. 실행할 함수 선택 > delete trigger 
