# divvup deployment tools

This repository is a set of tools I built to familiarize myself with Docker and various
github tools/integrations. Obviously there are already tools out there that do the things
that the tools in this repository do, but I wanted a deeper understanding of what was going
on under the hood.

## List of tools/descriptions


1. **status_checks** -  this checks for various debug statements and other undesireable code  
                    content that a developer might have left when originally opening a pull
                    request. It uses the github api to create a new status on a pull request
                    to confirm if the PR conforms to the code standards outlined above
