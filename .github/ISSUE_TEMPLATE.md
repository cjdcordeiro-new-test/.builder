---
title: [{{ env.BUILD_STATUS }}] ubuntu-rocks build for {{ env.BUILD_ROCK_PROJECT }}
labels: announcement
---

Just finished the CI/CD pipelines for ROCK project {{ env.BUILD_ROCK_PROJECT }}.

## Build report

Status: {{ env.BUILD_STATUS }}
ROCK project: [{{ env.BUILD_ROCK_PROJECT }}]({{ env.BUILD_ROCK_PROJECT_URL }})
Source branch: {{ env.BUILD_FROM_BRANCH }}
Source commit: {{ env.BUILD_FROM_COMMIT }}

---

Published ROCKs: {{ env.BUILD_PUBLISHED_ROCKS }}
Git tags: {{ env.BUILD_GIT_TAGS }}

---
Build logs: {{ env.BUILD_LOGS_URL }}
