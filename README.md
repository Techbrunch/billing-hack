# Billing Hack

This application allows to impersonate the Google Play Billing service (com.android.vending).

This is an updated version of [Billing Hack](https://github.com/dschuermann/billing-hack/blob/master/README.md) by [@domschuermann](https://twitter.com/domschuermann)

## How to use

1. Install Billing Hack
2. Patch the vulnerable application to use Billing Hack instead of the Google Play Billing service
3. Patch the vulnerable application performing the signature validation
4. Install the modified application in your device.

## References

- 2013 - [Google Play In-App Billing Library Hacked](https://web.archive.org/web/20140327052928/https://sufficientlysecure.org/index.php/2013/10/29/google-play-billing-hacked/)
- 2017 - [AbusingAndroid In-appBillingfeaturethanksto a misunderstoodintegration](https://www.securingapps.com/blog/BsidesLisbon17_AbusingAndroidInappBilling.pdf)
- 2018 - [Get Freebies by Abusing the Android InApp Billing API](https://www.checkmarx.com/blog/abusing-android-inapp-billing-api/)
- 2020 - [Contournement de l'API Google Play Billing](https://www.youtube.com/watch?v=OpAkXT5cZxw)