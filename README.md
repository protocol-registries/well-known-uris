# Well Known URI Registration Requests

This repository's issues list manages requests to add and change entries in the [well-known URI IANA registry](https://www.iana.org/assignments/well-known-uris/). Please note our [contribution terms](.github/CONTRIBUTING.md).

Your [Expert](https://tools.ietf.org/html/rfc8126#section-4.6) is currently [@mnot](https://github.com/mnot).

## Making a Request

To request registration of a new well-known URI (or a change to an existing one), you can:

* [File an issue](https://github.com/protocol-registries/well-known-uris/issues/new/choose) (preferred), or
* Send e-mail to [the mailing list](https://www.ietf.org/mailman/listinfo/wellknown-uri-review).

See [RFC8615](https://tools.ietf.org/html/rfc8615) for more information about well-known URIs; in particular, the [requirements for registration](https://tools.ietf.org/html/rfc8615#section-3.1).

Once approved, your request will be incorporated into the IANA registry, whereupon it will be officially registered.

### Choosing the Right Status

Values defined by standards-defined specifications will have a status of "permanent"; most others will have a status of "provisional." See the [guidance]([https://httpwg.org/http-core/draft-ietf-httpbis-semantics-latest.html#fields.registry](https://www.rfc-editor.org/rfc/rfc8615.html#section-3.1)) for details. Note that we use [this list](https://www.iana.org/assignments/iesg-recognized-organizations/iesg-recognized-organizations.xhtml#organizations) to determine what is a recognised standards organisation.

As per [IANA guidelines](https://www.rfc-editor.org/rfc/rfc8126.html#section-9.6), field names that are no longer in use should be marked as "obsoleted", and those whose use is not recommended should have a status of "deprecated". 

### Suitable Specification References

This registry requires a stable reference for a specification document. Publication by a recognised open standards body is preferred; however, publication by established Open Source projects (i.e., those that demonstrate a community that's commited to ongoing support), community and commercial organisations are also accepted, provided that they have a reasonable plan to promote specification stability.

## When to Register

Generally, a registration request should be made when your document is mature enough for wide review. 

If your reference is an Internet-Draft, the normal time to request registration is around the same time you request other reviews; e.g., Working Group Last Call or IETF Last Call. If you are unsure about your use of well-known URIs, request registration earlier. Note that if you do not request registration here, IANA will do so as part of their process. 

If your reference is in another standards body, a provisional registration can be made before the document is finalised, becoming permanent once it is published (if appropriate).

If your reference is from an Open Source project, community or commerical group, a request can be made once your document becomes public, but anticipatory requests are discouraged, and may be refused or delayed.
