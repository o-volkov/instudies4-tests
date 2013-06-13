instudies4-tests
================

Автоматизированные тесты

запуск:
# export DISPLAY=:99
# export DISPLAY=:99 && java -classpath ./bin:/usr/lib/selenium/selenium-server-standalone-2.33.0.jar org.testng.TestNG testng.xml


# Полный testng.xml
<!DOCTYPE suite SYSTEM "http://testng.org/testng-1.0.dtd" >
  
<suite name="InstudiesAutotests" verbose="1" >
  <test name="Autotests">
    <classes>
      <class name="com.instudies.autotests.RegisterTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.LoginTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.RegisterVkTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.RegisterFbTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.RegisterMrTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.RegisterTwTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.LoginVkTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.LoginFbTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.LoginMrTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.LoginTwTest"/>
      <class name="com.instudies.autotests.ActivateEmailTest"/>
      <class name="com.instudies.autotests.LogoutTest"/>
      <class name="com.instudies.autotests.RestorePassword"/>
    </classes>
  </test>
</suite>