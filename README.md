# unit-test-example
An Unit Test Example leveraging RSpec, Capybara and Selenium (w/ Chrome) via Docker-Compose

# STEP-1:
docker-compose up -d website selenium

# STEP-2:
docker-compose run --rm unit-tests

# visual verification is also possible via VNC to the selenium container on port 5901 (password:"secret") 

# Finish testing:
docker-compose down
