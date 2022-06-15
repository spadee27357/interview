在account和password的input格中輸入
有新增、取得、編輯、刪除 四個按鍵
分別對應至PHP四個不同的function

新增:
API url:user/data?type=Y&account="+ account + "&password=" + password
API 呼叫方式:POST

輸入account和password後按下新增鍵
透過API丟置PHP，並把account和password存入至SQL


取得:
API url:user/data?type=Y
API 呼叫方式:GET

按下取得鍵
透過API丟置PHP，並把現有SQL內的所有資料叫出來


編輯:
API url:user/data?type=Y&account="+ account + "&password=" + password
API 呼叫方式:POST

輸入account和password後按下編輯鍵
透過API丟置PHP，並把account和password重新UPDATE


刪除:
API url:user/data?type=Y&account="+ account
API 呼叫方式:POST

輸入account後按下刪除鍵
透過API丟置PHP，把該筆account從SQL內刪除
