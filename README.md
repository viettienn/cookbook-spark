spark-cookbook
=======================

This cookbook helps you to install Apache Spark.

Requirements
------------

e.g.
#### packages
- `toaster` - spark-cookbook needs toaster to brown your bagel.

Attributes
----------
TODO: List your cookbook attributes here.

e.g.
#### spark-cookbook::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['spark-cookbook']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### spark-cookbook::default

Just include `spark-cookbook` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[spark-cookbook]"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Tien Nguyen
