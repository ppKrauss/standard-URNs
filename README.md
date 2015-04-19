standard-URNs
-------------

In nowadays [**URN**](https://en.wikipedia.org/wiki/Uniform_resource_name) (Uniform Resource Name) is a low-use standard, is near to abandoned as "architectural solution" in [SOA](https://en.wikipedia.org/wiki/Service-oriented_architecture) and other architectures.

The necessity to "resolve URNs" can't to wait the [many-years IANA assignment process](http://www.iana.org/assignments/uRN-Namespaces/uRN-Namespaces.xml), neither the URN-Namespace "registration desire" of *de facto* URNs (like [DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)). The "potential URN user communities", local and/or international, need to use URNs to *"Give Things Names, Not Just Addresses"*, and these communities are as legitimate as IANA to assign their official namespaces.

Traditional URN architecture assumes a DNS-based [Resolution Discovery Service (RDS)](https://tools.ietf.org/html/rfc2276) to find the service appropriate to the given *URN scheme*; but no such widely deployed RDS schemes currently exist... However a user community not need to wait the day when RDS mechanisms supporting URN specifications become widely available. The only thing that the community need is some consensus about what is a relevant URN-Namespace and its URN-Resolver.

The more simple and basic URN resolution task is to check if a name exist. See *isN* resolver command of [RFC2169](http://tools.ietf.org/html/rfc2169).

## Objetive ##
List consensual URN-Namespaces that have also a public resolution mechanism, and describe some basic and util attributes of these URN-Namespaces.

This project is also a *open `git` colaboration space* for discuss the relevant attributes, the curatorial process, etc.

## How to use ##
.. see the `datapackage.json` the little `standard-URNs.csv` file, you can use it in server or client applications ...

----

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">standard-URNs</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">ppkrauss</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/ppKrauss/standard-URNs" rel="dct:source">https://github.com/ppKrauss/standard-URNs</a>.
