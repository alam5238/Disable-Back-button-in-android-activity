# Disable-Back-button-in-android-activity
A simple way to disable android activity back button pressed. 
When any one pressed back button on smart phone in background of android system called onBackPressed() method and follow method instruction.

---

We can simple disable this method. 

```
@Override
public void onBackPressed(){
  super.onBackPressed();  //just removed this line
}

```
Just removed `super.onBackPressed();` line.

Follow on Web:
http://bd.nas-tec.ml/blog/2017/12/02/disable-back-button-in-android-activity/
