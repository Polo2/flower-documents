# Quelques commandes curl pour tester le MCP server & MCWrapper

GET /*server_path/debug/:flow_id?input1=value1&input2=value2

Weather sur staging

server_path: https://dataplane-koyeb.staging.bump.sh/bump/weather-polo/debug
flow_id: weather_current
city=lyon

URL: https://dataplane-koyeb.staging.bump.sh/bump/weather-polo/debug/weather_current?city=lyon

curl -I  \
  --request GET "https://dataplane-koyeb.staging.bump.sh/bump/weather-polo/debug/weather_current?city=lyon" \
  --header "Authorization: Bearer toto"

GET /*server_path/debug/:flow_id?input1=value1&input2=value2
