veracode_static_scan:  
  profile: "35055 - Java Sample App for EP Tools (internal Facing)"
  
  push:
    trigger: false
    branches_to_run:
    branches_to_exclude:

  pull_request:
    trigger: false
    action:
      - opened
      - synchronize
    target_branch:
      - default_branch

  analysis_on_platform: true
