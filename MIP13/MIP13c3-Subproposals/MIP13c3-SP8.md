# MIP13c3-SP8: Maker Protocol Cover with Nexus Mutual (Declaration of Intent)

## Preamble

    MIP13c3-SP#: 8
    Author(s): Hugh Karp (@hughkarp)
    Contributors: n/a
    Status: Formal Submission (FS)
    Date Proposed: 2020-11-09
    Date Ratified: <yyyy-mm-dd>
    Declaration Statement: Maker Governance wishes to engage Nexus Mutual to provide cover for the Maker Protocol.
    Declaration to Replace: n/a

## Specification

### Context and Motivation

* The Maker Protocol burns MKR in good times when surplus is being generated and mints MKR in bad times when debt is accrued. As was demonstrated on Black Thursday this tends to result in MKR being burned at high prices and minted at low prices.
* It can be beneficial to purchase cover on Nexus Mutual that provides DAI when bad debt accrues to dampen MKR minting, with the cover purchase being paid for using high MKR prices.
* Recognizing this procyclical nature of MKR minting and burning, MakerDAO wishes to purchase tailored cover on Nexus Mutual to provide DAI claims when material bad debt is accrued by the protocol.
* Over cycles this is expected to result in a lower MKR supply.
* MakerDAO may also benefit from more material tail risk coverage in the future which can be worked towards as Nexus Mutual grows as it would be a relatively easy extension of the proposed solution.

The following is declared:

### Declaration Detail

* Provided pricing is at or below 4% pa (to be discussed in RFC stage), MakerDAO wishes to purchase four (4) tranches of Maker Protocol Cover of 3,000,000 DAI per tranche for a period of 365 days (up to 12,000,000 DAI total) on the basis of the following claims payment terms:

  1. If the Maker Protocol accrues bad debt of more than 5,000,000 DAI in any 30 day period, one tranche of 3,000,000 DAI claim will be paid; and
  2. If the Maker Protocol accrues bad debt of more than 10,000,000 DAI in any 30 day period an additional tranche of 3,000,000 DAI claim will be paid; and
  3. If the Maker Protocol accrues bad debt of more than 15,000,000 DAI in any 30 day period an additional tranche of 3,000,000 DAI claim will be paid, and
  4. If the Maker Protocol accrues bad debt of more than 20,000,000 DAI in any 30 day period an additional trance of 3,000,000 DAI claim will be paid, up to a maximum of four (4) tranches and a total claim payment of 12,000,000 DAI.
  5. Maker Protocol bad debt definition to be defined in detail through discussions with the working group (see below), so that a) it is simple to determine if a claim should be paid; and b) can't arbitrarily be triggered by MKR holders; and c) doesn't weaken MKR holders incentives to build surplus.

*Note: the above is a suggested framework and can be altered through discussion with working group.*

* The MakerDAO community, wishes to enact a working group titled “Maker Protocol Cover Group” led by TBA to:

  1. Review the claims wording before it is launched on Nexus Mutual to start the price discovery process, in particular the specific definition of bad debt and how it can be measured in the Maker Protocol; and
  2. Review if any changes should be made to the Maker Protocol to ensure flop auctions can be avoided via direct claim payment into the protocol; and
  3. Determine the best way for MakerDAO to technically interact with Nexus Mutual’s smart contracts including;     a) the cover purchase process;  b) payments made from the Maker Protocol; and     c) submission of claims.
  4. Review the pricing threshold and claims payout structure outlined in the declaration detail and make changes if considered appropriate.

### Relevant Links

[MakerDAO Protocol Cover Using Nexus Mutual](https://forum.makerdao.com/t/makerdao-protocol-cover-using-nexus-mutual/4761)

[Presentation to Governance and Risk Meeting](https://youtu.be/0v3E_kpLxFg?t=3066)
