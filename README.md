# Profile
curl -X POST --user "apikey:{apikey}" \
--header "Content-Type: text/plain;charset=utf-8" \
--header "Accept: application/json" \
--data-binary @{path_to_file}profile.txt \
"https://gateway.watsonplatform.net/personality-insights/api/v3/profile?version=2017-10-13"
