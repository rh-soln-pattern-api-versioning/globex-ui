# GlobexUi


## Running in local

Run `npm run dev:ssr` for running this as server side app. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## ENV variables

API_MANAGEMENT_FLAG=YES
API_USER_KEY_NAME
API_USER_KEY_VALUE
API_GET_PAGINATED_PRODUCTS
API_GET_PRODUCT_DETAILS_BY_IDS
API_TRACK_PLACEORDER



## Docker

docker build . -t quay.io/rh_soln_pattern_api_versioning/globex-ui:9f9edd0 -t quay.io/rh_soln_pattern_api_versioning/globex-ui:v1.1

docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:9f9edd0
docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:v1.1



docker build . -t quay.io/rh_soln_pattern_api_versioning/globex-ui:v1.1 -t quay.io/rh_soln_pattern_api_versioning/globex-ui:v1.1
docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:v1.1


docker build .  -t quay.io/rh_soln_pattern_api_versioning/globex-ui:86955bc -t quay.io/rh_soln_pattern_api_versioning/globex-ui:v2.0
docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:86955bc
docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:v2.0



docker build . -t quay.io/rh_soln_pattern_api_versioning/globex-ui:latest
docker push quay.io/rh_soln_pattern_api_versioning/globex-ui:latest
