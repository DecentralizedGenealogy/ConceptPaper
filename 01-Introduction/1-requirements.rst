########################################
    Requirements Overview
########################################


The software itself is a problem already solved by many people and the complexity is reasonable.

To find other instances having overlapping trees we need to:
1. get a starting point for communication to other instances
2. share a sample to match against
3. define some "levels of trust" to start sharing and validating the tree overlap and provide a communication entry
   point (like telling each other the contact email so the users can start mailing each other
   or even share a phone number and then meet personally
4. bind subtrees together to directly share data added at one instance

to 1.: a central service is necessary here because this seems the easiest way to
catch instances interested in sharing data. They only have to call this
service to send samples or get some samples to look for a match.

to 2.: As a central service should not have "real" data of people matching should be based on a hashed value.
As names may be mistyped or just typed differently on different countries this can not be used.
Dates of birth should be a better candidate. If one takes its birthdate, the birthdays of ones parents,
of the grandparents and the great-grandparents (so 15 dates in total) and build a md5 checksum on these dates
this should be a strong fingerprint.
Only the ID of this entry in the database, the ID of the originating instance and the checksum has to be stored on the
central server for some time so other instances can grab that checksum and try to find a matching entry in their own
database. If there is a match the instances can start to talk to each other directly.

to 3.: two instances may share only few data first so owners of other instances may check if this data seems valid.
Two instances may also share checksums over subtrees of the original sample to verify the data really is equal and it
is not a collision of the checksum.

to 4.: I also had some thoughts here but this can be discussed a lot later.


========================================
    Meta
========================================

.. container:: formalpara-title

   **Contents**

Short description of the functional requirements, driving forces,
extract (or abstract) of requirements. Link to (hopefully existing)
requirements documents (with version number and information where to
find it).

.. container:: formalpara-title

   **Motivation**

From the point of view of the end users a system is created or modified
to improve support of a business activity and/or improve the quality.

.. container:: formalpara-title

   **Form**

Short textual description, probably in tabular use-case format. If
requirements documents exist this overview should refer to these
documents.

Keep these excerpts as short as possible. Balance readability of this
document with potential redundancy w.r.t to requirements documents.

See `Introduction and Goals <https://docs.arc42.org/section-1/>`__ in
the arc42 documentation.
