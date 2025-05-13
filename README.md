# Normalization

## 1NF Conditions:
<ol>
  <li>Atomic values. No column has multiple valued comma separated.Example: Name column (X,Y) </li>
  <li>Unique column name.</li>
  <li>Positional dependency of data. Ordering does not matter. Data must be same after ordering.</li>
  <li>Column should contain that are of same type data</li>
  <li>Determine primary key</li>
</ol>


## 2NF Conditions:
<ol>
  <li>Must be in 1NF</li>
  <li>No partial depedencies.Sometimes composite primary key creates partial dependencies.</li>
  <li></li>
</ol>

## 3NF Conditions:

<ol>
  <li>Must be in 2NF.</li>
  <li>No transitive dependencies</li>
</ol>
