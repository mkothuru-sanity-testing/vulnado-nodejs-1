veracode_static_scan:  
  profile: "35055 - Java Sample App for EP Tools (internal Facing)"
  
  push:
    trigger: false
    branches_to_run:a
    branches_to_exclude:s

  pull_request:
    trigger: false
    action:
      - opened
      - synchronize
    target_branch:
      - default_branch

