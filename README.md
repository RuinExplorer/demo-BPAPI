# BPAPI
UBUG 2023 demonstration of Ellucian's Business Process APIs. Includes examples of several general person functions, some student specific functions, the ellucian integration pub/sub model, and an example utilizing student holds.

# eLive2023 Presentation
- Look for presentation 1634 in the technical track for a deep dive into the why behind this appraoch.

# Environment Veriables
```json
{
	"local_integraiton_url": "https://api-zdevl.banner.usu.edu/IntegrationApi/api",
	"local_student_url": "https://api-zdevl.banner.usu.edu/StudentApi/api",
	"local_business_url": "https://api-zdevl.banner.usu.edu/BannerAdminBPAPI/api",
	"access_token": "",
	"api_key": "",
	"auth_url": "https://integrate.elluciancloud.com/auth",
	"proxy_url": "https://integrate.elluciancloud.com/api",
	"pubsub_url": "https://integrate.elluciancloud.com/consume"
}
```

# Notes
The local_ environment variables would be used in conjunction with direct connection to on-prem api servers. This helps when testing proxy access through the Ellucian Integration Hub, but note the authentication and headers will be different. Keys are used for elluciancloud, basic auth is used for direct access to on prem api servers.
