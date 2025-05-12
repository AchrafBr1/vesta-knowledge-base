# VESTA 434

## Introduction

This guide will explain how the integration of the megaphone with VESTA works. You'll learn about the setup process, key features, and how to maximize the effectiveness of this integration.

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p><a href="https://bydemes.com/es/productos/cctv/accesorios/audio-profesional/VESTA-434">VESTA-434</a></p></figcaption></figure>

## 🔐 Local access

The following is the local access data to the horn:

<table data-header-hidden><thead><tr><th width="350"></th><th></th></tr></thead><tbody><tr><td>DEFAULT IP</td><td>192.168.5.200</td></tr><tr><td>DEFAULT USER NAME</td><td>admin</td></tr><tr><td>DEFAULT PASSWORD</td><td>admin</td></tr></tbody></table>

## Load new audio file

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>To load new mp3 file</p></figcaption></figure>



{% hint style="info" %}
Remember to enable en ALARM -> HTTP URL (Play File Enable)
{% endhint %}

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>



## 📢 HTTP commands for running audio spots in VESTA

### 🔊 **API Play Action Examples**

**Stop Action:**&#x20;

* http://192.168.0.155/api/play?action=stop

**Start playing bell1:**&#x20;

* http://192.168.0.155/api/play?action=start\&file=bell1

**Start playing userfile1 once with volume 10**:&#x20;

* http://192.168.0.155/api/play?action=start\&file=userfile1\&mode=once\&volume=10

**Start playing userfile1 multiple times (10 times) with volume 20:**

* http://192.168.0.155/api/play?action=start\&file=userfile1\&mode=multiple\&count=10\&volume=20

**Start playing userfile1 for a specific duration (10 times) with volume 30:**&#x20;

* http://192.168.0.155/api/play?action=start\&file=userfile1\&mode=duration\&count=10\&volume=30

## Activating an audio wedge from VESTA

{% hint style="success" %}
These **HTTP** commands can go directly into VESTA rule actions. For example, we can program a rule that in case of alarm will launch audio wedge 1 on the megaphone: We create a rule with the following:&#x20;



* _**TRIGGER:** Alarm -> Any alarm_&#x20;
* _**CONDITIONS:** Na_&#x20;
* _**ACTIONS:** HTTP ->_ http://192.168.0.155/api/play?action=start\&file=<mark style="color:red;">userfile1</mark>
  * _<mark style="color:red;">userfile1</mark>_: This is the first mp3 file we uploaded on the horn
{% endhint %}

<figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Rule example in VESTA</p></figcaption></figure>

