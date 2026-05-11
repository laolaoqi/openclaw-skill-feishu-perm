# Feishu Permission Manager Skill Pack

## Description
Permission management for documents and files. Add/remove collaborators with granular control.

## Quick Install
```
openclaw skills enable feishu-perm
```

**Warning:** Disabled by default. Enable explicitly in config.

## Features
- List collaborators on documents/folders
- Add collaborators (email, open_id, group, department)
- Remove collaborators
- Permission levels: view, edit, full_access

## Configuration
```yaml
channels:
  feishu:
    tools:
      perm: true
```

## Required Permissions
drive:permission

## License MIT