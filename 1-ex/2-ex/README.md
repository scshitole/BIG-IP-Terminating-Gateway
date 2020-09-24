# Setup AWS Access Key & Secret Key


1. Click on “Cloud Accounts” tab on the UDF Blue print

2. Copy the API Key & API Secret key

3. Go to the ubuntu UDF Shell and configure the following

```
 aws configure

    AWS Access Key ID [****************CGGT]:XXXXXXXXXXXXX

    AWS Secret Access Key [****************QmTY]:XXXXXXXXXXX
```

4. Change directory to `cd consul-tg-env` and execute `make all`
 
   ![alt text](../../images/makefail.png)

## Note :: Do Control C  to break it & follow step 5 below

5. Login to AWS Console by going to UDF Blueprint –> Cloud Accounts –> Console URL

6. Use the https link above `OptInRequired: In order to use this AWS Marketplace product you Error`

7. Click on https://console.aws.amazon.com/marketplace/home?region=us-west-2#/subscriptions/U1VCU0NSSVBUSU9OQEBAOTI5Y2EwZDgtYzJkNy00MDY4LThmOWEtZWI3NWE2NzdhZmVk

or

8. search for F5 BIG-IP Virtual Edition - BEST (PAYG, 1Gbps)

9. Sunsbcribe to the trial service and Accept all terms.


