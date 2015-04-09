# LoginFacebook
Facebook sdk 4.0 version

# App ID등록
string.xml
    <string name="app_id">YOUR APP ID</string>

AndroidManifest.xml
    <meta-data
        android:name="com.facebook.sdk.ApplicationId"
        android:value="@string/app_id" />
    <meta-data
        android:name="com.facebook.sdk.ApplicationName"
            android:value="@string/facebook_app_name" />
    <provider
        android:name="com.facebook.FacebookContentProvider"
        android:authorities="com.facebook.app.FacebookContentProviderYOUR_APP_ID"
        android:exported="true" />


# Change the LoginButton Text
    <string name="com_facebook_loginview_log_in_button_long">페이스북으로 로그인</string>
    <string name="com_facebook_loginview_log_out_button">로그아웃</string>
두 개를 value/string에 추가합니다.

# remove icon
    loginButton.setCompoundDrawablesWithIntrinsicBounds(0, 0, 0, 0);//아이콘 없애기
앞에 있는 페이스북 아이콘이 사라집니다.
