# LoginFacebook
Facebook sdk 4.0 version

# App ID등록
    <string name="app_id">YOUR APP ID</string>
    

# Change the LoginButton Text
    <string name="com_facebook_loginview_log_in_button_long">페이스북으로 로그인</string>
    <string name="com_facebook_loginview_log_out_button">로그아웃</string>
두 개를 value/string에 추가합니다.

# remove icon
        loginButton.setCompoundDrawablesWithIntrinsicBounds(0, 0, 0, 0);//아이콘 없애기
앞에 있는 페이스북 아이콘이 사라집니다.
