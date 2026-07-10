# SECASS & VESTA - ARC setup guide

Easy step-by-step instructions to connect your VESTA alarm panel to the SECASS monitoring center.

## What You Need Before Starting

<table><thead><tr><th width="188">Item</th><th>Description</th></tr></thead><tbody><tr><td><strong>Subscriber ID</strong></td><td>A 6-digit number given to you by SECASS (e.g., <code>123456</code>)</td></tr><tr><td><strong>SECASS Server IP</strong></td><td><code>195.198.14.12</code></td></tr><tr><td><strong>SECASS Secondary Server IP</strong></td><td><code>195.198.116.108</code></td></tr><tr><td><strong>SECASS Port for Events</strong></td><td><code>23507</code></td></tr><tr><td><strong>SECASS Port for Images</strong></td><td><code>23506</code></td></tr></tbody></table>

{% hint style="info" %}
Keep your Subscriber ID handy. You'll use it in both steps below.
{% endhint %}

## Part 1: Event Reporting

This sends alarm events (arming, disarming, intrusions, etc.) from your panel to SECASS in real time.<br>

<figure><img src=".gitbook/assets/image (1322).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
#### On your VESTA panel, go to Configuration → Report
{% endstep %}

{% step %}
#### Tap **Add** to create a new reporting URL
{% endstep %}

{% step %}
#### Fill in the fields as follows

```
URL:  ip://SUBSCRIBER_ID@195.198.14.12:23507/SIA2
```

{% hint style="info" %}
Replace `SUBSCRIBER_ID` with the 6-digit number SECASS gave you.

Example: if your ID is `123456`, the URL becomes `ip://123456@195.198.14.12:23507/SIA2`
{% endhint %}
{% endstep %}

{% step %}
#### Under **Group**, select **Group 2**

{% hint style="warning" %}
This is important. Events won't reach SECASS if you leave it on the wrong group.
{% endhint %}
{% endstep %}

{% step %}
#### Save the configuration
{% endstep %}
{% endstepper %}

### Quick Check

<table><thead><tr><th width="192">Setting</th><th>Value</th></tr></thead><tbody><tr><td>Protocol</td><td>SIA2 (<code>/SIA2</code> at the end of the URL)</td></tr><tr><td>Server IP</td><td><code>195.198.14.12</code></td></tr><tr><td>Port</td><td><code>23507</code></td></tr><tr><td>Group</td><td><strong>Group 2</strong></td></tr><tr><td>Subscriber ID</td><td>Your 6-digit ID from SECASS</td></tr></tbody></table>

<figure><img src=".gitbook/assets/image (1323).png" alt=""><figcaption></figcaption></figure>

## Part 2: Image Capture Reporting

This sends snapshots from PIRCAMS and IP cameras to SECASS when an alarm is triggered.

{% stepper %}
{% step %}
#### On your VESTA panel, go to **Configuration** → **Captured Files**
{% endstep %}

{% step %}
#### Tap **Add** to create a new URL
{% endstep %}

{% step %}
#### Select the protocol: **manitou**
{% endstep %}

{% step %}
#### Fill in the address field

```
SUBSCRIBER_ID@195.198.14.12:23506
```

{% hint style="info" %}
Replace `SUBSCRIBER_ID` with the same 6-digit number from Part 1.

Example: if your ID is `105928`, the address becomes `105928@195.198.14.12:23506`
{% endhint %}
{% endstep %}

{% step %}
#### Save the configuration
{% endstep %}
{% endstepper %}

### Quick Check

<table><thead><tr><th width="183">Setting</th><th>Value</th></tr></thead><tbody><tr><td>Protocol</td><td>manitou</td></tr><tr><td>Server IP</td><td><code>195.198.14.12</code></td></tr><tr><td>Port</td><td><code>23506</code></td></tr><tr><td>Subscriber ID</td><td>Your 6-digit ID from SECASS</td></tr></tbody></table>

<figure><img src=".gitbook/assets/image (1324).png" alt=""><figcaption></figcaption></figure>

## Summary - Both URLs at a Glance

<table><thead><tr><th width="170">What it does</th><th>Menu Path</th><th>URL Format</th></tr></thead><tbody><tr><td><strong>Event Reporting</strong></td><td>Configuration → Report</td><td><code>ip://SUBSCRIBER_ID@195.198.14.12:23507/SIA2</code></td></tr><tr><td><strong>Image Capture</strong></td><td>Configuration → Captured Files</td><td><code>SUBSCRIBER_ID@195.198.14.12:23506</code> (protocol: manitou)</td></tr></tbody></table>

## Troubleshooting

<table><thead><tr><th width="288">Problem</th><th>What to Check</th></tr></thead><tbody><tr><td>Events not reaching SECASS</td><td>Make sure you selected <strong>Group 2</strong> in the Report settings</td></tr><tr><td>Images not sending</td><td>Verify the protocol is set to <strong>manitou</strong>, not MAN</td></tr><tr><td>Both failing</td><td>Double-check your Subscriber ID — it must match the one SECASS assigned to you</td></tr><tr><td>Still not working</td><td>Confirm the panel has internet access and the SECASS server is reachable at <code>195.198.14.12:23506</code></td></tr></tbody></table>

## Common Mistakes

* **Wrong group** — Event reporting must use Group 2
* **Swapped protocols** — Events use `SAI2`, images use `manitou`. Don't mix them up.
* **Missing `/SIA2`** — The event URL must end with `/SIA2`
* **Wrong subscriber ID** — Same ID goes in both URLs, exactly as provided by SECASS

_Need help? Contact SECASS & VESTA support with your Subscriber ID ready._

