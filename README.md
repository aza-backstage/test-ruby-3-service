<!--TO_BE_REMOVED-->

# THIS WILL BE REMOVED WHEN THE TEMPLATE IS SUCCESSFULLY GENERATED.

## IF YOU ARE STILL SEEING THIS ON THE README, PLEASE CHECK THE ACTIONS TAB FOR THE "RAILS GENERATOR INIT PROJECT" ACTION.

## YOU CAN MANUALLY TRIGGER IT IF IT FAILS TO GENERATE THE TEMPLATE AND REMOVE THIS TEXT

### END

<!--TO_BE_REMOVED-->

# Test Ruby 3 Service

Description.

## Local build

To build the container use:

1. `bundle package --all`
2. `rm -rf vendor/bundle`
3. `docker build -t test-ruby-3-service .`

To run the app in the container use:

`docker run -p 3510:3000 test-ruby-3-service:latest`

## Dependencies

In order to reasonably run this container you need a working API that you are able to connect to.

To run use:

`bundle exec rails s -p 3510 -b 0.0.0.0`

## Deployment

Deployment is done by a CI/CD pipeline. Merge or push to either staging or production branches automatically triggers a deployment to staging and production environment respectively.
