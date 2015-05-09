standard-URNs
-------------

In nowadays [**URN**](https://en.wikipedia.org/wiki/Uniform_resource_name) (Uniform Resource Name) is a low-use standard... But is,  among other things, an "conceptual solution" in [SOA](https://en.wikipedia.org/wiki/Service-oriented_architecture) and microservices... And perhaps a [good solution for some Schema.org problems](https://github.com/schemaorg/schemaorg/issues/405).

The necessity to "resolve URNs" not need to wait the [many-years IANA assignment process](http://www.iana.org/assignments/urn-namespaces), neither the URN-Namespace "registration desire" of *de facto* URNs (like [DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)). The "potential URN user communities", local and/or international, need to use URNs to *"Give Things Names, Not Just Addresses"*[[1]](http://www.persid.org/initiative.html), and these communities are as legitimate as IANA to assign their official namespaces in their scope.

## Objective ##
List consensual URN-Namespaces (of a community) that have also a public resolution mechanism, and describe some basic and util attributes of these URN-Namespaces.

This project is also a *open `git` collaboration space* for discuss the relevant attributes, the curatorial process, etc.
## How to use ##
.. see the `datapackage.json` the little `standard-URNs.csv` file, you can use it in server or client applications ...

* **[`standard-URNs.csv`](data/standard-URNs.csv) -  [community](https://docs.google.com/spreadsheets/d/1UuzXGcsGAn9UBYstmUvlaDHmNYo_-vxgvXC-dev_bFU/edit?usp=sharing)** - community building list and attributes.
* [`urn-namespaces-1.csv`](data/urn-namespaces-1.csv) - [community](https://docs.google.com/spreadsheets/d/1u_Few2f6XcNjY67qGGJ934SAYqLqP-0-y-tVfDAjrGw/edit?usp=sharing) - the [IANA list](http://www.iana.org/assignments/urn-namespaces/urn-namespaces-1.csv), enhanced with a "Used" column.

## Technical notes ##
This project is focused on the use of IANA and non-IANA URNs that can be usefull and that can be resolved. The URL-Resolver concept adopted here is the "standard" [Wikipedia and RFC 2141/2169/3406/3986 concept](https://en.wikipedia.org/wiki/Uniform_resource_name#Resolvers), that can be illustred by DOI, [WorldCat](http://www.worldcat.org/xissn/titlehistory), etc. or by an local application like [ISSN-L resolver](https://github.com/okfn-brasil/ISSN-L-Resolver).

"Old" traditional URN architecture assumes a DNS-based [Resolution Discovery Service (RDS)](https://tools.ietf.org/html/rfc2276) to find the service appropriate to the given *URN scheme*; but no such widely deployed RDS schemes currently exist... However a user community not need to wait the day when RDS mechanisms supporting URN specifications become widely available. The only thing that the community need is some consensus about what is a relevant URN-Namespace and its URN-Resolver.

As defined by [RFC3406-sec3.1](http://tools.ietf.org/html/rfc3406#section-3.1), there are the "Experimental Namespaces", taking the form `URN:X-<NID>`, that are not explicitly registered with IANA. It is extremally informal. The community need a minimal standarization process for reliable conventions, and minimal persistence/stability in its implementation.  This gap of formality can be also filled by this project, see the proposal of `urn:x-ok` as "OKFN community standard".

## Prepare ##
Methodology in the `/data/*.csv` files contruction.
 
...

----

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">standard-URNs</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">ppkrauss</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/ppKrauss/standard-URNs" rel="dct:source">https://github.com/ppKrauss/standard-URNs</a>.
