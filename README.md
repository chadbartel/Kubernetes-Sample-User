# Kubernetes Sample User

This Kubernetes project creates a service role and binds the service role to access the Kubernetes dashboard.

1. Run `create_roles.sh` to create and bind the role.

2. Run `get_bearer_token.sh` to get a bearer token from the role.

3. Run `run_dashboard.sh` to run the Kubernetes dashboard service.

4. Navigate to the url in `dashboard_url.txt` to access the Kubernetes dashboard and provide the token from the previous step.

5. Run `cleanup.sh` to remove the created role.
