

testbed for ideas....


### Cross Version Analysis

{% include cross-version-analysis.xhtml %}

{% capture cross-version-analysis %}{% include cross-version-analysis.xhtml %}{% endcapture %}
bar {{ cross-version-analysis | remove: '<p>' | remove: '</p>'}} foo

### IG Dependencies

This IG Contains the following dependencies on other IGs.

{% include dependency-table.xhtml %}

### Global Profiles

{% include globals-table.xhtml %}

### Copyrights
{% capture ip-statement %}{% include ip-statements.xhtml %}{% endcapture %}

{{ ip-statement | remove: '<p>' | remove: '</p>'}}


