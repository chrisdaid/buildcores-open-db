# OpenDB Licensing Research

**Historical research:** this analysis and custom draft review preceded the local implementation. Research was checked September 30, 2026. On October 1, the local setup selected unmodified CC BY-NC-SA 4.0 for future eligible material, preserved earlier ODC-By permissions, and added separate standard-license agreement templates. See the [current licensing guide](../README.md) and [scope notice](../../../NOTICE.md). The custom draft files below remain alternatives, not operative terms.

**Earlier recommendation:** for the explicit rules proposed in the custom package, the custom BuildCores OpenDB Community License was the closest policy fit. For free noncommercial use, ShareAlike on protected shared adaptations, and separate commercial permission, unmodified CC BY-NC-SA 4.0 was the preferred standard option and is now selected locally. Either approach needs an express contributor grant, separate commercial agreements, and identified new material that BuildCores can license. A custom license is not necessary merely to keep the original noncommercial restriction attached to forks.

## Draft documents

| Document                                                | Purpose                                                                                                      |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| [Community license](COMMUNITY_LICENSE_DRAFT.md)         | Free noncommercial use, attribution, reciprocal shared forks, and separate BuildCores commercial permission  |
| [Contributor agreement](CONTRIBUTOR_AGREEMENT_DRAFT.md) | Permission for BuildCores to license accepted contributions commercially while contributors retain ownership |
| [Commercial agreement](COMMERCIAL_AGREEMENT_DRAFT.md)   | Customer-specific written approval with release, use, distribution, price, and term limits                   |
| [Release notice](RELEASE_NOTICE_DRAFT.md)               | Identify covered new material, legacy rights, excluded content, and notices that forks must preserve         |

## Previously published permissions

The [repository license at the time of research](https://github.com/buildcores/buildcores-open-db/blob/main/LICENSE.txt) is **Open Data Commons Attribution 1.0**. Its section 3.1 permits commercial use. Section 4.4 preserves the original license offer downstream and prohibits additional restrictions on that grant; section 9.5 preserves existing permissions if a different license is later offered. The README at that time also identified ODC-By; the [preserved license text](../ODC-By-1.0.txt) records those terms. These are express permissions, not merely an omission of a commercial prohibition. [Official ODC-By text](https://opendatacommons.org/licenses/by/1-0/).

ODC-By principally addresses rights in a database, and section 2.4 separates rights in individual contents. A license notice does not establish ownership of every field, photograph, or manufacturer document appearing in or linked from a database. [Official ODC-By scope](https://opendatacommons.org/licenses/by/1-0/).

The CONTRIBUTING.md inspected during the initial research requested accurate data and sources, but contained no express grant allowing BuildCores to commercialize or relicense all contributor-owned protected material. No separate CLA was found in the inspected repository files. Existing private contributor or employment agreements were not available for this review. GitHub's default contribution terms refer to a repository's existing license, subject to a separate agreement; they are not a substitute for the broader grant proposed here. [GitHub terms, section D.6](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#d-user-generated-content).

## Why this license structure fits

The requested policy has three parts: noncommercial community use without individual approval, separate permission for commercial use, and the same rules on redistributed protected forks. The proposed public license addresses all three directly. The commercial agreement states what a customer is allowed to do. The contributor agreement gives BuildCores authority to grant commercial permissions in accepted contributions.

These are distinct grants. A customer's approval does not rewrite the public license for every recipient. A fork's obligation to use the same noncommercial terms does not give BuildCores ownership or commercial sublicensing authority over that fork author's additions.

| Candidate                                                | Fit for this policy                       | Reason                                                                                                                                                                              |
| -------------------------------------------------------- | ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ODC-By 1.0, license at the time of research              | Does not fit                              | Commercial use is expressly allowed; no reciprocal licensing of additions                                                                                                           |
| ODbL 1.0                                                 | Does not fit the commercial gate          | Database reciprocity is useful, but commercial use remains permitted                                                                                                                |
| CC BY-NC 4.0                                             | Partial fit                               | Restricts commercial exercise of licensed rights, but lacks ShareAlike for the adapter's protected contributions                                                                    |
| CC BY-NC-SA 4.0                                          | Best standard alternative                 | Combines noncommercial permission with reciprocity for shared protected adaptations, and includes applicable database rights                                                        |
| CDLA Sharing 1.0                                         | Does not fit                              | Data-specific reciprocity, but section 3.3 expressly prohibits adding commercial-use restrictions                                                                                   |
| PolyForm Noncommercial 1.0.0                             | Poorer fit for this database              | A software-oriented grant without an equivalent explicit sui generis database-rights and database-reciprocity structure; some organizational allowances are broader than this draft |
| Business Source License 1.1 or Functional Source License | Does not fit a continuing commercial gate | Designed around eventual conversion to a more permissive license                                                                                                                    |
| Commons Clause                                           | Does not implement this policy            | A software “Sell” restriction is narrower than requiring approval for all defined commercial uses                                                                                   |
| Proposed custom Community License                        | Closest policy fit                        | Explicit commercial examples, expense funding, fixed downstream terms, database scope, and legacy carveouts; requires legal review and custom compliance handling                   |

Sources: [ODbL](https://opendatacommons.org/licenses/odbl/1-0/), [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en), [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt), [CDLA Sharing](https://cdla.dev/sharing-1-0/), [PolyForm Noncommercial](https://polyformproject.org/licenses/noncommercial/1.0.0), [BSL 1.1](https://mariadb.com/bsl11/), [FSL](https://fsl.software/), and [Commons Clause](https://commonsclause.com/). The ranking is a recommendation based on the requested policy, not a conclusion by those license stewards.

ODC's published license set does not provide a standard noncommercial ODC-By variant. Do not amend ODC-By or CC wording and retain their official names or badges. This proposal uses a distinct name and does not claim approval by those organizations. [ODC licenses](https://opendatacommons.org/licenses/), [Creative Commons guidance on modified licenses](https://creativecommons.org/faq/#can-i-change-the-license-terms-or-conditions).

## How fork restrictions work

The public draft uses several separate provisions to prevent a fork from presenting the covered database as commercially unrestricted:

1. Section 4.2 keeps the commercial restriction attached to protected material through a mirror, renamed fork, changed file format, or combined database.
2. Sections 5.1 and 5.2 require the same license text and the same public permissions for protected database changes that a fork shares.
3. Section 5.3 bars a weaker replacement license, removal of BuildCores' approval requirement, and automatic permission to commercialize after a time delay.
4. Section 6 requires original source, license, commercial contact, legacy notices, and an indication of changes.

Keeping a derivative within an organization does not require publication. Giving a copy to an independent person or organization triggers the shared-copy requirements even when the transfer is private. Recipients may exercise the noncommercial sharing rights in their copies; confidentiality terms cannot remove those rights. A contractor processing solely on the project's behalf is excepted and can be bound by confidentiality and limits on independent reuse. This is deliberately broader reciprocity than CC BY-NC-SA's public Sharing trigger. [CC BY-NC-SA definition of Share and section 3(b)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt).

This is stronger policy specificity than a bare “noncommercial” sentence in a README. It still operates only within applicable rights. Someone can use their own original work separately, exercise legal exceptions, or rely on an existing ODC-By grant.

**Important fork boundary:** commercial permission for an entire modified fork can require two sets of permissions: BuildCores' for controlled original material, and the fork authors' for protected additions. The public draft deliberately does not silently grant BuildCores commercial rights in every outside fork. The separate contributor agreement covers only people who expressly accept it and the contributions it identifies. If centralized commercial licensing of every fork's additions is desired later, that would require an additional explicit grant and a separate policy decision.

Under the standard alternative, CC BY-NC already keeps the original noncommercial restriction on original licensed material; ShareAlike adds obligations for shared protected adaptations. CC BY-NC-SA sections 3(b) and 4 address those adaptations and applicable database rights. Neither license assigns fork authors' copyrights to BuildCores. [CC BY-NC-SA legal text](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt).

## Proposed treatment of common uses

These are drafting choices, not existing OpenDB restrictions. Outcomes assume the new license actually covers rights needed for the use; sections 2.1 and 2.2 preserve legacy grants and statutory freedoms.

| Use                                                                                             | Proposed outcome                                                                                        | Relevant public draft section |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----------------------------- |
| Personal hardware research or hobby app                                                         | Free, no approval                                                                                       | 3.1 and 3.2                   |
| Free community part picker without monetization                                                 | Free, with attribution for protected public material                                                    | 3 and 6                       |
| Charity or university's mission-related noncommercial project, including paid staff             | Free                                                                                                    | 3.2 and 4                     |
| Voluntary donations or grants covering actual project costs without paid access or promotion    | Free                                                                                                    | 4.3                           |
| Paying an ordinary host or contractor to maintain the permitted project                         | Allowed on the project's behalf                                                                         | 3.3                           |
| Private transfer of a protected derivative to an independent nonprofit for its own use          | Same public terms on the received copy; an NDA cannot remove granted noncommercial sharing rights       | 3.4 and 5                     |
| Shared modified database fork                                                                   | Same public license on controlled database modifications; preserve notices                              | 5 and 6                       |
| Private noncommercial changes                                                                   | No duty to publish or contribute upstream                                                               | 3.4                           |
| Application code using the database                                                             | No automatic duty to license the application under this license                                         | 3.4                           |
| Ads, affiliate links, or paid promotional placements in a data-dependent project                | Commercial permission required                                                                          | 1 and 4.1                     |
| Paid API, subscriptions, paid dataset download, or nonprofit charging for data-dependent access | Commercial permission required                                                                          | 1 and 4.3                     |
| Free product operated for a business purpose, internal company tools, or a commercial prototype | Commercial permission required                                                                          | 1 and 4.1                     |
| Protected database use for a commercially intended model or training pipeline                   | Commercial permission required; no automatic licensing of all model outputs                             | 1, 2.2, and 4.1               |
| A renamed fork offering the covered database commercially                                       | BuildCores permission still required for controlled rights; fork additions may need separate permission | 4.2                           |
| Commercial reuse relying on an earlier valid ODC-By grant                                       | Earlier rights remain available                                                                         | 2.1                           |
| Independent facts or a legally permitted use requiring none of the licensed rights              | Not restricted by this license                                                                          | 2.2                           |

The revenue policy is intentionally explicit: ads and affiliates require commercial permission, while qualifying expense funding does not. There is no approved small-revenue threshold. This draft does not invent one. A nonprofit's separate fundraising site is not automatically commercial database use; the connection between the covered material and the revenue activity matters.

## Limits a license cannot remove

### Earlier releases remain commercially reusable

The current ODC-By permissions cannot simply be taken back. A previous compliant recipient or redistributor can keep relying on that license for its covered material. Renaming an old release, adding a new tag, or republishing the same file under new wording does not eliminate those permissions. A later version can contain separately restricted new protected material, but that is not a commercial prohibition on the earlier database. [ODC-By section 9.5](https://opendatacommons.org/licenses/by/1-0/).

An existing contributor's new commercial grant can help establish authority for future licensing. It cannot erase the contributor's earlier public grant. The transition needs a rights and release manifest rather than a blanket statement that every file is now exclusively noncommercial.

### Product facts may lack exclusive protection

The [data model](../../DATA_MODEL.md) describes public specifications, product identifiers, and retailer mappings. These features make copyright scope a practical issue for this particular database. The US Copyright Office distinguishes original compilation authorship from unprotected facts and mechanical ordering. Merely encoding a specification as JSON does not establish ownership of the specification. [US Copyright Office database guidance](https://www.copyright.gov/register/tx-databases.html).

Some original selection, arrangement, annotations, or protected contents may qualify, but this review does not establish protection for every record or the entire compilation. Do not promise that a license can prevent every competing database assembled from the same factual information. The draft therefore limits its conditions to actual rights requiring permission.

### Database rights vary by jurisdiction and rights holder

EU database protection can depend on qualifying investment, the nature of the extraction, and the maker's eligibility. Article 11's eligibility rules must be checked for the actual rights holder; merely having European users is not enough to establish that BuildCores holds those rights. Copyright originality is also a separate inquiry. [Directive 96/9/EC, particularly articles 3, 7, 8, 11, and 15](https://www.legislation.gov.uk/eudr/1996/9/pdfs/eudr_19960009_2019-06-06_en.pdf).

### Contract acceptance is a separate issue

A public rights license and a contract restricting access to a hosted service solve different problems. For API or download access, a clearly presented agreement with affirmative acceptance and retained records can support contractual obligations, subject to applicable law. A footer or README does not establish that every stranger accepted a contract. In _Berman_, the Ninth Circuit addressed conspicuous notice and unambiguous assent in online contracting under the law applicable there; it is not a universal ruling that every checkbox creates an enforceable agreement. [Official court opinion](https://cdn.ca9.uscourts.gov/datastore/opinions/2022/04/05/20-16900.pdf).

If BuildCores needs control that extends beyond protectable database material, a separately contracted hosted API or value-added service is the more suitable place to consider those obligations. It cannot retroactively bind public GitHub downloaders or remove their earlier permissions.

## Contributor and commercial workflow

The proposed contributor agreement expressly discloses commercial sublicensing and no automatic royalties, while leaving ownership with the contributor. Acceptance must identify the rights holder and the exact terms accepted. Use an organizational signatory where an employer owns the contribution, and identify any earlier contributions in a specific addendum. Do not treat historical pull requests as signatures.

A separate contributor grant is an established mechanism for clarifying licensing authority; the Apache contributor agreement illustrates a nonexclusive grant and employer authority checks. Its nonprofit obligations and software patent terms are not a template for BuildCores' business policy. [Apache ICLA](https://www.apache.org/licenses/icla.pdf).

MusicBrainz provides a useful database precedent: its published approach distinguishes public data licenses and contributor permission for commercial licensing. Its core and supplementary data use different licenses, so it is a precedent for explicit authority and scoped releases rather than a claim that all MusicBrainz data is noncommercial. [MusicBrainz data licensing](https://musicbrainz.org/doc/About/Data_License).

The commercial draft makes approval specific to a customer, material, product, term, and downstream rights. Pricing is negotiated rather than incorporated from a changing website. The public fork and attribution obligations are expressly incorporated as conditions of the commercial grant unless the order identifies specific waivers. Commercial approval alone does not waive them or pass approval to arbitrary fork users. Rights in unreviewed outside fork additions are expressly excluded.

## Independent review and revisions

Two subagents independently reviewed the five drafts, repository license, and relevant primary sources. One focused on rights, licensing architecture, and enforceability limits; the other tested the community, commercial, and fork policies against practical uses. Both found the core structure consistent with the stated goals and agreed that standard CC BY-NC-SA already covers the basic noncommercial and fork requirement.

Their review resulted in two substantive corrections:

1. **Agency handling and confidentiality.** The earlier Share definition excepted processing solely on the project's behalf only from section 5.2. Sections 5.1 and 5.3 could still conflict with purpose-limited contractor access. The exception now covers section 5, preserves notices and independent permissions, and expressly permits confidentiality for that handling.
2. **Commercial grant and downstream duties.** The earlier commercial template did not clearly apply reciprocal obligations when a customer relied entirely on its commercial grant. Sections 5 and 6 of an identified adopted Community License now apply as express contractual conditions by default. Any waiver must identify the affected obligations, rights, distributions, and recipients; agency processing is separately addressed.

Both reviewers rechecked the revised provisions and confirmed that these corrections resolve their findings, with no material remaining ambiguity in that focused review. This confirms drafting consistency within the reviewed scope, not a legal opinion on enforceability.

The recommendation is now conditional on the intended policy. The custom option adds categorical commercial examples, expense funding, private onward-transfer reciprocity, and an exact-version requirement. Those are proposed business choices beyond the basic noncommercial and ShareAlike request, not user-approved exceptions or rules. The review did not establish BuildCores' ownership of every required right or replace jurisdiction-specific legal advice.

## Requirements before adoption

1. **Identify the contracting party and contact.** Fill the legal name and working commercial/contributor contact. Confirm the law and courts appropriate for commercial contracts; the public grant currently contains no invented choice of law.
2. **Establish rights and legacy scope.** Preserve the earlier ODC-By license and a known legacy release baseline. Audit rights in selected new material and original compilation features. Map contributor, employee, contractor, and third-party permissions. A record being new does not prove it is protectable or exclusively owned.
3. **Complete the contributor process.** Present the commercial grant before acceptance, record the exact agreement and identity privately, and block inclusion of protected submissions without adequate authority. Obtain specific grants for old contributions where needed; missing permissions remain unresolved.
4. **Review the custom legal language.** Have qualified counsel check the protected database scope, reciprocity, expense-funding exception, termination, contributor grant, customer liability terms, and relevant jurisdictions. Those are the material review issues arising from this repository and proposed business policy.
5. **Publish an identified release package.** Adopt a finalized license and complete coverage notice together. Update the README and contribution instructions in the same change, preserve legacy permissions, and carry notices in exported archives and mirrors. Do not imply that all historical data has become restricted.
6. **Use explicit commercial approvals.** Retain the completed customer scope and accepted terms. Account for raw exports, downstream sublicensing, model use, and expiration before signing. A zero-fee agreement is available for a commercial use BuildCores chooses to approve without charge.

These are adoption requirements for the proposed licensing change, not a claim that they have already been completed. No exhaustive contributor-ownership or third-party provenance audit has been performed. No commercial pricing, legal entity, release cutoff, or jurisdiction has been inferred from the repository.

## Naming and tradeoff

A noncommercial restriction prevents the data from meeting the Open Definition's allowance for use for any purpose. OpenDB may remain the project's name, but public descriptions should explain “free for noncommercial community use; commercial use by separate license” and avoid representing the new terms as unrestricted open data or an OSI-approved open-source license. [Open Definition 2.1](https://opendefinition.org/od/2.1/en/).

The custom approach gives BuildCores clearer policy language at the cost of familiar standard-license tooling and reuse compatibility. Do not assume it is compatible with third-party CC BY-NC-SA material: that license's protected adaptations generally need its prescribed adapter license, while this custom draft requires its own exact version. Combining protected material can therefore require separate permission or separation of independent databases. [CC BY-NC-SA section 3(b)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt).

If those stricter choices and custom-license overhead are not needed, use unmodified CC BY-NC-SA 4.0 for properly identified material, retain appropriate contributor and commercial agreements, and publish a separate explanation that does not add incompatible license restrictions. Using the standard option also requires corresponding changes to the contributor promise, commercial order, incorporated obligations, and release notice; this custom package cannot be adopted unchanged with a different license name.
