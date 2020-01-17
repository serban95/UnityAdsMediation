# UnityAdsMediation</br></br>

**AdMob**</br>
**AdColony**</br></br>

Import **Unity Package** to existing or to a new Project<br/><br/>
![Image1](images/1.png)<br/>
These folders should be at **Assets** or **Root Folder**<br/><br/>

![Image2](images/2.png)<br/>
The platform target should be **Android**<br/><br/>

![Image3](images/3.png)<br/>
Inside Assets Menu, locate **Play Services Resolver -> Android Resolver -> Resolve**<br/><br/>

![Image4](images/4.png)<br/>
Message when **Resolved**<br/><br/>

![Image5](images/5.png)<br/>
Time to add **AdMob** Android **App ID**<br/>
Locate to **Assets Menu -> Google Mobile Ads -> Setting**<br/><br/>

![Image6](images/6.png)<br/>
Check **Google Ad Mob** - **Enabled**<br/>
Add **AdMob Android App Id** string<br/><br/>

![Image7](images/7.png)<br/>
Locate Prefab at **AdMediation** -> **Prefabs** Folder<br/><br/>

![Image7_1](images/7_1.png)<br/>
Into a Scene add the **AdsManager** Prefab<br/>
The Hierarchy should be like the Image<br/><br/>

![Image8](images/8.png)<br/>
Select Prefab's GameObject in the Scene **AdMediation** and add **AdMob** strings<br/><br/>

![Image8_1](images/8_1.png)<br/>
Add **Ad Units** to **MoPubManager** <br/><br/>

![Image8_2](images/8_2.png)<br/>
Add **Interstitial Ad Units** and **Rewarded Ad Units** to **MoPubDemoScene** <br/><br/>

![Image8_3](images/8_3.png)<br/>
Inside **IronSource** GameObject, Add **Unique User Id** and **AppKey** <br/><br/>

![Image9](images/9.png)<br/>
![Image10](images/10.png)<br/>
**AdsManager** Prefab GameObject include an Script **AdsManager**<br/>
This **Script** includes methods to show Interstitila Ads and Rewarded Ads<br/><br/>

![Image11](images/11.png)<br/>
These methods could be called within a Click or from other Script Component<br/><br/>

![Image12](images/12.png)<br/>
**AdsManager** exposes callbacks from the Ads State<br/><br/>
