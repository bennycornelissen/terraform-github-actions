FROM bennycornelissen/terraform:0.11.11

LABEL "com.github.actions.name"="terraform apply"
LABEL "com.github.actions.description"="Run terraform apply"
LABEL "com.github.actions.icon"="book-open"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/bennycornelissen/terraform-github-actions"
LABEL "homepage"="http://github.com/bennycornelissen/terraform-github-actions"
LABEL "maintainer"="Benny Cornelissen <mail@bennycornelissen.nl>"

RUN apk --no-cache add jq

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
