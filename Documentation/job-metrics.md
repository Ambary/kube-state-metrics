# Job Metrics

| Metric name| Metric type | Labels/tags |
| ---------- | ----------- | ----------- |
| kube_job_info | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_spec_parallelism | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_spec_completions | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_spec_active_deadline_seconds | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_status_active | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_status_succeeded | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_status_failed | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_status_start_time | Counter | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_status_completion_time | Counter | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_complete | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_failed | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
| kube_job_created | Gauge | `job`=&lt;job-name&gt; <br> `namespace`=&lt;job-namespace&gt; |
