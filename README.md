<!DOCTYPE HTML
  PUBLIC "-//W3C//DTD XHTML 1.0 Transitional //EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xmlns:v="urn:schemas-microsoft-com:vml"
  xmlns:o="urn:schemas-microsoft-com:office:office">
<head>
    <meta charset="UTF-8">
    <title>FM Sales Report</title>
</head>
<body style="margin:0; padding:0; background:#f5f5f5;">

    <!-- 1st div: Banner with logo and date -->
    <div style="width: 100%; height: 100%; padding-left: 20px; padding-right: 20px; padding-top: 18px; padding-bottom: 18px; background: #020B43; justify-content: space-between; align-items: center; display: inline-flex">
        <div style="width: 110px; height: 43px; position: relative; overflow: hidden">
            <img style="width: 130px; height: 69px; left: -13px; top: -13px; position: absolute" src="{{ scb_logo }}" />
        </div>
        <div style="color: white; font-size: 12px; font-family: SC Prosper Sans, Arial, sans-serif; font-weight: 500; word-wrap: break-word">
            {{current_date}}
        </div>
    </div>

    <!-- 2nd div: Custom Daily Update section -->
    <div style="width: 100%; height: 100%; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex; margin-top: 10px;">
        <div style="width: 2px; align-self: stretch; background: #38D200; overflow: hidden; border-radius: 100px; flex-direction: column; justify-content: flex-start; align-items: flex-start; display: inline-flex">
            <div style="align-self: stretch; flex: 1 1 0; padding: 10px; background: #0473EA; border-radius: 100px"></div>
            <div style="align-self: stretch; flex: 1 1 0; padding: 10px; background: #38D200"></div>
        </div>
        <div style="width: 483px; height: 33px; flex-direction: column; justify-content: center; align-items: flex-start; display: inline-flex">
            <div style="align-self: stretch; height: 32px; color: black; font-size: 26px; font-family: SC Prosper Sans; font-weight: 400; word-wrap: break-word">Daily Update</div>
        </div>
        <div style="width: 193px; justify-content: flex-start; align-items: center; gap: 6px; display: flex">
            <!-- Logo goes here -->
            <div style="width: 26px; height: 26px; position: relative">
                <img src="{{ cap_logo }}" style="width: 26px; height: 26px; object-fit: contain;" alt="Logo" />
            </div>
            <div style="color: black; font-size: 11px; font-family: SC Prosper Sans; font-weight: 500; word-wrap: break-word">Commercial Analytics Platform</div>
        </div>
    </div>

    <!-- 3rd div: Custom message section -->
    <div style="width: 100%; height: 100%; position: relative; margin-top: 10px;">
        <div style="width: 702px; left: 0px; top: 0px; position: absolute; color: #0473EA; font-size: 18px; font-family: Inter; font-weight: 700; word-wrap: break-word">
            {{name}}
        </div>
        <div style="left: 0px; top: 32px; position: absolute; justify-content: flex-start; align-items: center; gap: 14px; display: inline-flex">
            <div style="width: 485px">
                <span style="color: black; font-size: 12px; font-family: Inter; font-weight: 400; word-wrap: break-word">
                    Your CAPFM analytics have been refreshed with the latest data.<br/>
                    A snapshot of key metrics has been provided below to keep you up to date. CAPFM uses FM OneSales for coverage entitlements. If you have questions on your data below, please speak to the 
                </span>
                <a href="mailto:FMSalesCOOTeam@sc.com" style="color: #0473EA; font-size: 12px; font-family: Inter; font-weight: 500; text-decoration: underline; word-wrap: break-word">
                    FM COOs
                </a>
                <span style="color: black; font-size: 12px; font-family: Inter; font-weight: 400; word-wrap: break-word">
                    to check your coverage entitlements.
                </span>
            </div>
            <div style="width: 186px; position: relative; flex-direction: column; justify-content: flex-start; align-items: center; gap: 12px; display: inline-flex">
                <div style="width: 165px; text-align: center; color: black; font-size: 12px; font-family: Inter; font-weight: 600; word-wrap: break-word">
                    For full details
                </div>
                <a href="http://go/cap" style="width: 165px; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #0473EA; font-size: 14px; font-family: SC Prosper Sans; font-weight: 700; text-decoration: underline; line-height: 16px; word-wrap: break-word">
                    Access CAP FM Now
                </a>
            </div>
        </div>
    </div>


    <!-- 4th div: FVC at a glance section -->
    <div style="width: 100%; height: 100%; flex-direction: column; justify-content: flex-start; align-items: center; gap: 10px; display: inline-flex; margin-top: 10px;">
        <div style="align-self: stretch; height: 24px; padding-left: 233px; padding-right: 233px; padding-top: 4px; padding-bottom: 4px; background: #0473EA; justify-content: center; align-items: center; gap: 10px; display: inline-flex">
            <div style="justify-content: center; display: flex; flex-direction: column; color: white; font-size: 12px; font-family: SC Prosper Sans; font-weight: 700; line-height: 16px; word-wrap: break-word">
                Your FVC at a glance on {{ prev_day }}
            </div>
        </div>
        <div style="justify-content: flex-start; align-items: center; gap: 18px; display: inline-flex">
            <div style="width: 110px; flex-direction: column; justify-content: flex-start; align-items: center; gap: 10px; display: inline-flex">
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #00172E; font-size: 9px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    {{ prev_day }}
                </div>
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    {{ prev_day_FVC }}
                </div>
            </div>
            <div style="width: 110px; flex-direction: column; justify-content: flex-start; align-items: center; gap: 10px; display: inline-flex">
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #00172E; font-size: 9px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    MTD
                </div>
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    ${{ mtd_FVC }}
                </div>
            </div>
            <div style="width: 110px; flex-direction: column; justify-content: flex-start; align-items: center; gap: 9px; display: inline-flex">
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #00172E; font-size: 9px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    MTD MoM%
                </div>
                <div style="justify-content: flex-start; align-items: center; display: inline-flex">
                    <div style="text-align: center; justify-content: center; display: flex; flex-direction: column; color: #C32121; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                        {{ mtd_mom_pct_FVC }}
                    </div>
                </div>
            </div>
            <div style="width: 110px; flex-direction: column; justify-content: flex-start; align-items: center; gap: 10px; display: inline-flex">
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #00172E; font-size: 9px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    YTD
                </div>
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    ${{ ytd_FVC }}
                </div>
            </div>
            <div style="width: 110px; flex-direction: column; justify-content: flex-start; align-items: center; gap: 10px; display: inline-flex">
                <div style="align-self: stretch; text-align: center; justify-content: center; display: flex; flex-direction: column; color: #00172E; font-size: 9px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                    YTD YoY%
                </div>
                <div style="justify-content: flex-start; align-items: flex-end; gap: 4px; display: inline-flex">
                    <div style="text-align: center; justify-content: center; display: flex; flex-direction: column; color: #419C37; font-size: 14px; font-family: Inter; font-weight: 500; line-height: 16px; word-wrap: break-word">
                        {{ ytd_yoy_pct_FVC }}
                    </div>
                </div>
            </div>
        </div>
        <div style="width: 100%; text-align: center; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 10px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word; margin-top: 10px;">
            Source: CIB Data Analytics Store as of {{ prev_day }}. This data originates from Product Control on a T-2 day basis.
        </div>
    </div>



    <!-- 5th div: YTD FVC & CI by Product section -->
    <div style="width: 100%; height: 100%; padding-left: 233px; padding-right: 233px; padding-top: 4px; padding-bottom: 4px; background: #38D200; justify-content: center; align-items: center; gap: 10px; display: inline-flex; margin-top: 10px;">
        <div style="justify-content: center; display: flex; flex-direction: column; color: white; font-size: 12px; font-family: SC Prosper Sans; font-weight: 700; line-height: 16px; word-wrap: break-word">
            Your YTD FVC and CI by Product on {{ prev_day }} (USD)
        </div>
    </div>
    <div>
        <style type="text/css">
            {{ css_Product|safe }}
        </style>
        {{ producttable|safe }}
    </div>

    <!-- 6th div: Daily Revenue by Client section -->
    <div style="width: 100%; height: 100%; padding-left: 233px; padding-right: 233px; padding-top: 4px; padding-bottom: 4px; background: #525355; justify-content: center; align-items: center; gap: 10px; display: inline-flex; margin-top: 10px;">
        <div style="justify-content: center; display: flex; flex-direction: column; color: white; font-size: 12px; font-family: SC Prosper Sans; font-weight: 700; line-height: 16px; word-wrap: break-word">
            Your Daily Revenue by Client on {{ prev_day }} (USD)
        </div>
    </div>
    <div>
        <style type="text/css">
            {{ css_Client|safe }}
        </style>
        {{ clientTable|safe }}
    </div>

    <!-- 7th div: Confidentiality notice -->
    <div style="width: 100%; height: 100%; padding-left: 130px; padding-right: 130px; padding-top: 25px; padding-bottom: 25px; background: #020B43; justify-content: center; align-items: center; gap: 10px; display: inline-flex">
        <div style="flex: 1 1 0; text-align: center; color: white; font-size: 12px; font-family: SC Prosper Sans; font-weight: 400; word-wrap: break-word">
            The information in this email is to be treated as confidential and for the intended employee only. Please do not forward this email.
        </div>
    </div>

</body>
</html>
