Hey {{ .hub_admins }}! :wave
I notice there is still pending information about the new hub deployment.
The information pieces still missing, are the ones listed below.

{{#features}}
  features!!!!!!!!
{{\features}}
 
- {{ .auth_type }}
- {{ .hub_admins }}
- {{ .github_auth_only_how_would_you_like_to_manage_your_users }}
- {{ .github_teams_auth_only_profile_restriction_based_on_team_membership }}
- {{ .hub_logo_url }}
- {{ .hub_logo_info }}
- {{ .hub_image_repo }}
- {{ .hub_image_registry }}
- {{ .features }}
- {{ .cloud_provider }}
- {{ .billing_account }}
- {{ .other_information }}
- {{ .tasks_to_deploy }}

Details about each of them can be found in the top comment. But if you have questions about any of them, please ping the "2i2c/engineering" and they will help you.

After the form in the top comment is filled in, an engineer will be assigned and will start deploying the new hub 🚀.
Thank you!
