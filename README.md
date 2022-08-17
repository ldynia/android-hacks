# Android Hacks
[read](https://technastic.com/remove-samsung-bloatware-safe-to-remove-apps/)

```bash

adb shell
pm list packages | sort
adb shell pm list packages | sort > packages.md
```
## Samsung Galaxy A53 - Bloatwer packages

```bash
{
  pm uninstall -k --user 0 com.aura.oobe.samsung.gl;
  pm uninstall -k --user 0 com.enhance.gameservice;
  pm uninstall -k --user 0 com.facebook.appmanager;
  pm uninstall -k --user 0 com.facebook.katana;
  pm uninstall -k --user 0 com.facebook.services;
  pm uninstall -k --user 0 com.facebook.system;
  pm uninstall -k --user 0 com.google.android.apps.tachyon;
  pm uninstall -k --user 0 com.google.android.apps.wellbeing;
  pm uninstall -k --user 0 com.google.android.apps.youtube.music;
  pm uninstall -k --user 0 com.google.android.gm;
  pm uninstall -k --user 0 com.google.android.videos;
  pm uninstall -k --user 0 com.google.vr.vrcore;
  pm uninstall -k --user 0 com.netflix.mediaclient;
  pm uninstall -k --user 0 com.samsung.android.app.notes;
  pm uninstall -k --user 0 com.samsung.android.app.notes.addons;
  pm uninstall -k --user 0 com.samsung.android.app.routines;
  pm uninstall -k --user 0 com.samsung.android.app.settings.bixby;
  pm uninstall -k --user 0 com.samsung.android.app.spage;
  pm uninstall -k --user 0 com.samsung.android.app.vrsetupwizardstub;
  pm uninstall -k --user 0 com.samsung.android.ardrawing;
  pm uninstall -k --user 0 com.samsung.android.aremoji;
  pm uninstall -k --user 0 com.samsung.android.aremojieditor;
  pm uninstall -k --user 0 com.samsung.android.arzone;
  pm uninstall -k --user 0 com.samsung.android.authfw;
  pm uninstall -k --user 0 com.samsung.android.beaconmanager;
  pm uninstall -k --user 0 com.samsung.android.bixby.agent;
  pm uninstall -k --user 0 com.samsung.android.bixby.service;
  pm uninstall -k --user 0 com.samsung.android.bixby.wakeup;
  pm uninstall -k --user 0 com.samsung.android.bixbyvision.framework;
  pm uninstall -k --user 0 com.samsung.android.calendar;
  pm uninstall -k --user 0 com.samsung.android.da.daagent;
  pm uninstall -k --user 0 com.samsung.android.email.provider;
  pm uninstall -k --user 0 com.samsung.android.game.gamehome;
  pm uninstall -k --user 0 com.samsung.android.game.gametools;
  pm uninstall -k --user 0 com.samsung.android.game.gos;
  pm uninstall -k --user 0 com.samsung.android.gametuner.thin;
  pm uninstall -k --user 0 com.samsung.android.hmt.vrshell;
  pm uninstall -k --user 0 com.samsung.android.hmt.vrsvc;
  pm uninstall -k --user 0 com.samsung.android.ipsgeofence;
  pm uninstall -k --user 0 com.samsung.android.mateagent;
  pm uninstall -k --user 0 com.samsung.android.messaging;
  pm uninstall -k --user 0 com.samsung.android.oneconnect;
  pm uninstall -k --user 0 com.samsung.android.samsungpass;
  pm uninstall -k --user 0 com.samsung.android.samsungpassautofill;
  pm uninstall -k --user 0 com.samsung.android.scloud;
  pm uninstall -k --user 0 com.samsung.android.service.stplatform;
  pm uninstall -k --user 0 com.samsung.android.spay;
  pm uninstall -k --user 0 com.samsung.android.spayfw;
  pm uninstall -k --user 0 com.samsung.android.visionintelligence;
  pm uninstall -k --user 0 com.samsung.android.voc;
  pm uninstall -k --user 0 com.samsung.ecomm.global;
  pm uninstall -k --user 0 com.samsung.hidden.china;
  pm uninstall -k --user 0 com.samsung.phone.overlay.common;
  pm uninstall -k --user 0 com.samsung.sree;
  pm uninstall -k --user 0 com.samsung.systemui.bixby2;
  pm uninstall -k --user 0 com.sec.android.app.clockpackage;
  pm uninstall -k --user 0 com.sec.android.app.dexonpc;
  pm uninstall -k --user 0 com.sec.android.app.kidshome;
  pm uninstall -k --user 0 com.sec.android.app.kidsinstaller;
  pm uninstall -k --user 0 com.sec.android.app.popupcalculator;
  pm uninstall -k --user 0 com.sec.android.app.samsungapps;
  pm uninstall -k --user 0 com.sec.android.app.sbrowser;
  pm uninstall -k --user 0 com.sec.android.app.shealth;
  pm uninstall -k --user 0 com.sec.android.easyMover;
  pm uninstall -k --user 0 com.sec.android.easyMover.Agent;
  pm uninstall -k --user 0 com.sec.android.mimage.avatarstickers;
  pm uninstall -k --user 0 com.wsomacp;
  pm uninstall -k --user 0 de.axelspringer.yana.zeropage;
}
```
