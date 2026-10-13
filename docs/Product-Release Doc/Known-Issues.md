---
sidebar_position: 5
title: Known issues
---

# Known Issues and Workarounds in FlowSpace 2.0

**Release Version:** 2.0  
**Product:** FlowSpace Project Management Platform

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="npm" label="npm">

    ```bash
    npm install my-package
    ```

  </TabItem>
  <TabItem value="yarn" label="Yarn">

    ```bash
    yarn add my-package
    ```

  </TabItem>
</Tabs>


## Overview

This page documents known issues and current limitations in FlowSpace 2.0 that may affect the user experience. It also provides workarounds to help users continue working while a permanent resolution is being investigated or developed.

Review the relevant issue before contacting the support team to determine whether a workaround is available.

## 1. Dashboard Widgets May Load Slowly

### Issue Description

Dashboards containing a large number of widgets may take longer than expected to load. This can delay access to project metrics and task summaries.

### User Impact

- Dashboard information may take longer to appear.
- Users may experience delays when switching between dashboards.
- Monitoring project progress may take additional time.

### Workaround

1. Open the affected dashboard.
2. Review the number of widgets displayed.
3. Remove widgets that are not currently required.
4. Save the dashboard configuration.
5. Reload the dashboard and check whether loading performance improves.

### Current Status

Known issue. A permanent resolution has not been confirmed for this portfolio example.

---

## 2. Task Search May Return Delayed Results

### Issue Description

In some situations, recently created or updated tasks may not appear immediately in search results.

### User Impact

- Users may not find a task immediately after creating or updating it.
- Users may spend additional time searching for recently modified tasks.

### Workaround

1. Verify that the task was created or updated successfully.
2. Check the relevant project and task list directly.
3. Refresh the task list or repeat the search after a short interval.
4. If the task remains unavailable, contact the support team.

### Current Status

Known issue. Further investigation is required to determine the cause and confirm a permanent fix.

---

## 3. Notification Preferences May Take Time to Apply

### Issue Description

Changes to notification preferences may not take effect immediately. Users may continue receiving notifications based on their previous settings for a short period.

### User Impact

- Users may receive notifications they recently disabled.
- Changes to notification behavior may appear inconsistent immediately after saving preferences.

### Workaround

1. Open your profile menu.
2. Navigate to **Settings > Notifications**.
3. Verify that your preferred settings are saved.
4. Allow a short interval for the changes to take effect.
5. If the previous notification behavior continues, contact the support team.

### Current Status

Known issue. The timing of preference updates requires further investigation.

---

## Known Issues Summary

| Issue | User Impact | Workaround |
|---|---|---|
| Slow dashboard loading | Delayed access to dashboard information | Reduce the number of widgets displayed |
| Delayed task search results | Recently updated tasks may not appear immediately | Refresh the task list and verify the task in the project |
| Delayed notification preference updates | Previous notification settings may remain active temporarily | Verify saved preferences and allow time for changes to apply |

## When to Contact Support

Contact your support team if:

- The suggested workaround does not resolve the issue.
- The issue prevents you from completing an important task.
- You encounter an error message that is not covered in this document.
- The problem continues or occurs repeatedly.

When reporting an issue, include the following information:

- A description of the problem.
- The steps required to reproduce it.
- The expected and actual results.
- Any error messages or screenshots.
- The approximate time the issue occurred.

Do not include passwords, authentication tokens, or other sensitive information in support requests.

## Related Documentation

- [What's New](./What's-New.md)
- [New Features](./New-Features.md)
- [Improvements](./Improvements.md)
- [Bug Fixes](./Bug-Fixes.md)
- [Upgrade Notes](./Upgrade-Notes.md)
- [Previous Release](./Previous-Releases.md)

---

**Portfolio Note:** FlowSpace is a fictional project management platform created for a technical writing portfolio. The issues, workarounds, and statuses described above are illustrative examples, not verified defects in an actual product. In a real release, known issues and workarounds should be confirmed with the engineering and QA teams before publication.