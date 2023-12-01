# apigee-github-actions


curl -X POST -H "Authorization: Bearer $(gcloud auth application-default print-access-token)" https://apigee.googleapis.com/v1/organizations/deployapigee-406709/environments/test-env/apis/hello-world/revisions/2/deployments?override=true



curl -X POST https://apigee.googleapis.com/v1/organizations/deployapigee-406709/environments/eval/apis/hello-world/revisions/2/deployments?override=true

curl --fail -X POST -H \"Authorization: Bearer $(gcloud auth application-default print-access-token)\" \"https://apigee.googleapis.com/v1/organizations/deployapigee-406709/environments/eval/apis/hello-world/revisions/2/deployments?override=true\"

"curl --fail -X POST -H \"Authorization: Bearer ${{steps.auth.outputs.access_token}}\" \"https://apigee.googleapis.com/v1/organizations/${{ secrets.APIGEE_ORG }}/environments/eval/apis/hello-world/revisions/${{steps.upload.outputs.apigee-revision}}/deployments?override=true\""

gcloud auth application-default print-access-token

ya29.a0AfB_byCuHAsKABukEAavv0c66_wm0nP8w_ZT0_zgtkZ5tUBG2itM1DybeGyVDEyHCRov_jieHG1XK7ZAUBfBfWIRUdl9ZvMLHGpIH6ZYe6TpQ8GCOLJhm5mfjP0I_rX1RnLB4B9REcWkcXtpaq2q-9Ln7VIKu7pvgVIjigoPTVHYozGRP6MOc0eD5Uca2amJqOgJ1MvZEJX0atsyAQ8w5bKIcYPdHVCCQulP10Ule9SGeDOrP23seP34RmBkWqGVM0hFU2UfjfIQ3BCGjz1noAMzUFzymh-I3OvMXlSoG6nHalVKhgkAesIG2tcCkxZ2F4vASciE_CyA_F-OwMtKs-rFNVUsZWq4mmxzD8jB60CeqHIw49cSVWrtODTcnbBpZ0RgWjb61PxmdZejjmZsC7dWmWSN38xoaCgYKAakSARESFQHGX2MikV7HYWqyfA7J3zuDLLHKZg0423

$(gcloud auth application-default print-access-token)