# ansible-consul
Ansible role for a simple Consul installation


# Configuration

^ Settings                ^ Defaults                      ^ Description ^
| consul_version          | latest                        | changeme    |
| consul_arch             | linux_amd64                   | changeme    |
| consul_bin_dir          | /usr/local/bin                | changeme    |
| consul_etc_dir          | /usr/local/etc/consul.d       | changeme    |
| consul_systemd_dir      | /usr/local/lib/systemd/system | changeme    |
| consul_log_dir          | /var/log/consul               | changeme    |
| consul_data_dir         | /var/local/consul             | changeme    |
| consul_user             | consul                        | changeme    |
| consul_group            | consul                        | changeme    |
| consul_datacenter       | dc1                           | changeme    |
| consul_secret_key       |                               | changeme    |
| consul_retry_join       |                               | changeme    |
| consul_raft_multiplier  |                               | changeme    |
| consul_bootstrap_expect | 3                             | changeme    |
| consul_ui               | false                         | changeme    |

