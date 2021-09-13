# Enveloped JSON Signatures
This was spun off from Web of Things where a need was identified to add internal signatures to a WoT Thing Description.
Current JSON signature mechanisms, e.g. JWS, are external and "enveloping", and in addition don't support useful features
like chaining, partial signing (signing only a subset of the document), or multiple signatures.  The short-term goal of this
repo is to define an extension that can be used in WoT TDs for signing.  The long-term goal is to establish a basis for
an enveloped JSON signature standard that can be used for any JSON content.