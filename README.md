# Unity_Geofence_Notification-Demo

# Usage
1. Import [AndroidGeofence](https://github.com/haowenjhang/AndroidGeofence) .aar file in Plugins / Android
2. Add permission & receiver in AndroidManfest

   ```
   <receiver
    android:name="com.wen.geofencelib.GeofenceBroadcastReceiver"
    android:enabled="true"
    android:exported="true"
    android:allowBackup="true">
   </receiver>

   <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
   <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
   <uses-permission android:name="android.permission.ACCESS_BACKGROUND_LOCATION" />
   ```
