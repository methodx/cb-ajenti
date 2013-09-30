Cookbook-ajenti
========================
Installs Ajenti panel

Requirements
------------

apt
yum

Usage
-----
#### cookbook-ajenti::default

Just include `cookbook-ajenti` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[cookbook-ajenti]"
  ]
}
```