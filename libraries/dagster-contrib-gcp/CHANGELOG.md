# Changelog

## Local (unreleased)

### Internal

- Reapplied debug logging (`job_origin`, `current_code_location`, `job`) to `CloudRunRunLauncher`, originally added in commit `2745e2e` on this fork, carried forward through the upstream sync.

## 0.0.9

### Updated

- (pull/259) Added the `container_name` field option to support multi-container job launching

## 0.0.4

### Updated

- (pull/181) Fixed mutation of job configuration preventing repeat launches of the same job due to KeyError

## 0.0.4

### Updated

- (pull/145) Added support for launching CloudRun runs in multiple GCP Projects


## 0.0.3

### Updated

- (pull/88) Added job timeout as dagster.yaml instance config
