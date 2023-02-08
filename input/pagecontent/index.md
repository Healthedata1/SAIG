### Health eData Sandbox

testbed for ideas....

#### FOO

using http:

[US Core](http://hl7.org/fhir/us/core/STU4/index.html)

[FHIR](http://hl7.org/fhir/)



using https:

[US Core](https://hl7.org/fhir/us/core/STU4/index.html)

[FHIR](https://hl7.org/fhir/)

using path variable

[FHIR]({{site.data.fhir.path}})

#### in list...:

using http:


- [US Core](http://hl7.org/fhir/us/core/STU4/index.html)
- [FHIR](http://hl7.org/fhir/)

using https:

- [US Core](https://hl7.org/fhir/us/core/STU4/index.html)
- [FHIR](https://hl7.org/fhir/)

#### in table...:

using http:

|link|
|---|
|[US Core](http://hl7.org/fhir/us/core/STU4/index.html)|
|[FHIR](http://hl7.org/fhir/)|
{:.grid}

using https:

|link|
|---|
|[US Core](https://hl7.org/fhir/us/core/STU4/index.html)|
|[FHIR](https://hl7.org/fhir/)|
{:.grid}

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
~~~
{{ ip-statement | remove: '<p>' | remove: '</p>'}}
~~~

{{ ip-statement | remove: '<p>' | remove: '</p>'}}

### using {%raw%}{{site.data.resources[resource_].description}}{%endraw%}



by string

{%raw%}{{site.data.resources['ImplementationGuide/healthedata1-sandbox'].description \| markdownify}}{%endraw%}

with markdown filter

{{site.data.resources['ImplementationGuide/healthedata1-sandbox'].description | markdownify}}

without markdown filter

{{site.data.resources['ImplementationGuide/healthedata1-sandbox'].description}}


{% assign beatles = "John, Paul, George, Ringo" | split: ", " %}

{% for member in beatles %}
  {{forloop.index0}}: {{ member }}
{% endfor %}

