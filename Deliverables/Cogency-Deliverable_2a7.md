## Deliverable Number
2a.7

## Context

| Number        | Workshop      | Date         | Duration     |
| ------------- | ------------- |------------- |------------- |
| 7.1 | Defining the trigger, the digital asset and consumers (1/2) |21.11.2022 - 1PM CET|60min|
| 7.2 | Defining the trigger, the digital asset and consumers (2/2) |22.11.2022 - 5PM CET|60min|
| 7.3 | Sprint round up  |25.11.2022 - 4PM CET|60min|

During this sprint the focus has been on how to create value for both publishers and consumers (7.1 and 7.2) and, after gathering more information, an evolved version of our solution has been presented to the team (7.3).

## Output

In the first two sessions (7.1 and 7.2) the team has discussed about both publisher and consumer gains:

### Consumer gains and comments:
- It will improve service levels. It’s the system (blockchain) doing it automatically, not the publisher collecting the data.
- More ownership and control of the consumer’s digital identity/data.
- Badging for Tier-1 benefits: chat with editors, meetings, recommendations, etc.
- Increasing loyalty by the read to learn incentive using smart contracts automatically.
- The incentive should have a genuine value for users. Users may not care about fancy NFTs, or tokens with little value.
- Can the user interact with similar profiles by owning and knowing their digital identity?
- Unlocking content that other users can’t read because you are a super user.
- Receive fiat/tokens.
- Single sign in for a set of publishers - one login to have access for the content from all of them.
- Free trial for the paid content of a site that you are not a subscriber to.
- Data portability: content separated from the platform enables the content to be consumed offline.
- Sharing content between users. 
- The digital asset will be owned or will be the person itself - potential risk of malicious enrichment when sharing deliberately. 
- Ability to have more control over the ads. If the digital asset is bundled in a web package, you can choose a publisher that you trust regardless if the aggregator is trustworthy. 
- User engagement to foster interaction to help with credibility: if a user is a heavy politics reader, their opinions should have more credibility and influence. We should be careful with consent, but [Crumbs](https://crumbs.org/en/?cbs_source=eyeo_blog&cbs_medium=cta&cbs_campaign=crumbs_topics) can help.
- Consumers are not really worried about their data itself. They are most interested in what they can obtain in exchange for their data (monetisation). 
- Younger users' attention: Gen Z and above. Do they care about privacy?
  - [Data privacy summary](https://morningconsult.com/2022/11/09/data-privacy-is-different-for-gen-z/)
  - Gen Z is more interested in data/privacy
  - Gen Z is more fatalistic about privacy but it does impact their trust in brands
- Transparency on data collection:
  - Example: Spotify Wrapped model (most listened songs and artists). People are excited about that every year when it's basically a reflection of data collection.
  - Community stats to make decisions about a specific topic. Similar to a news feed.

### Publisher gains and comments:
- Compliance (GDPR).
- Engagement validation.
- Trust and loyalty.
- Cheaper storage.
- Increasing the user pool.
- What do we do with Tier-1 consumers (the ones more loyal to a brand)?
- Cross-publishing access: loyal/subscribed consumers (because they have a badge/token) from Site X can unlock the paywall for Site Y for a specific amount of time, with the aim that the consumer becomes a Site Y subscriber. 
- More synergies between publishers. 
- Aggregators:
  - On the one hand, we won’t need aggregators (which are currently in web2), so middlemen wouldn’t be needed. Aggregators are currently very expensive and skipping them would be a game changer. We could use the money saved from aggregators for users (free trials, for instance, to convert them).
  - But on the other hand, aggregators can also work for specific use cases: to enhance local publications and increase reach. 
  - Aggregators such as [Distributed Media Lab](https://www.distributedmedialab.com/) and [Smart News](https://www.smartnews.com/en/) are top “publishers” just for the sake of being aggregators.
  - The problem of aggregation tools is that they have been, thus far, [extractive](https://twitter.com/Chronotope/status/751489068572246017).
  - Can we really disrupt the aggregators? It would be very interesting for the publishers, but [aggregators are very well established](https://techcrunch.com/2021/09/15/news-aggregator-smartnews-raises-230-million-valuing-its-business-at-2-billion/).
- Relation between Site X and Site Y will become key to enrich the user experience and content. Aggregators wouldn’t be playing the game.
- Site Y will be able to decrease their budget for acquiring new users because the subscribed user from Site X will spread the word (network effects). Free opportunity to give a first impression. And more users will come.
- Increase content distribution, and be more direct. 
- Trusted news feed so the user doesn’t need to go, for instance, to Twitter. This will retain users and keep them more engaged.
- Potential risk: content syndication working process is still open. Mitigation plan: the first site will hold the IP and can get a better monetisation than the ones that syndicate that piece of news (revenue share/licence).
- Getting a token fee by giving the token to the consumer.
- IPFS will decrease the publisher infrastructure cost and will increase content reach, but IPFS is still very expensive.

Based on the first two meetings, the team has come up with an evolved approach of the solution (7.3), outlined during the previous sprint.

### Creating the Digital Identity

<img width="900" alt="image" src="https://user-images.githubusercontent.com/114009050/208780106-a880f501-1a6b-40d9-9e29-2590bac1c312.png">

The process starts in the CMS, where the publisher creates the piece of content that will be consumed. From all users interacting with the piece of content, we’ll focus on three different groups: 

1. Premium reader: a user that has decided to increase their subscription expenditure for a publication.
2. Heavy reader, given a defined consumption threshold.
3. Young reader, given a defined age threshold.

Once a user belongs to one of the previous three groups, a trigger will be released, which will unleash the creation of the consumer’s digital asset: the creation of a unique profile of their data that is theirs alone, and people can only see if they give them access. The digital identity is not tied to a single publisher, it’s tied to the consumer.

The digital asset will be based on consumer’s metadata, that will be initially gathered in a form filled out by the consumer, who will be asked to complete additional information and informed that they will own their own data: not the publisher, not the platform, but the consumer themselves. The form will be also used for the user to give consent for their data to be stored to avoid any future GDPR issue. 

In return, the consumer gets a unique NFT profile created on-chain plus a token that the publisher will also obtain.


### The Digital Identity creates win-win user acquisition and retention

Once the digital identity is created, as the consumer consumes content, all the metadata is gathered by their digital asset, that is their unique digital identity bundled in an NFT. 

Some real scenarios:

1. The more the user is engaged, that is, the more they read or interact with the publisher content, their badge will increase in value (e.g. bronze to silver), and more tokens will be distributed among all parties.
2. The user can subscribe to a different publisher who, depending on the consumer’s badge, can give away giftable content for their family and friends, a discount, or more tokens for both parties. 

<img width="900" alt="image" src="https://user-images.githubusercontent.com/114009050/208780173-eade8af7-3cc1-4a50-bcdb-b1ee9e236abc.png">

This process will also be an incentive for the publisher beyond acquiring a new consumer, because some others could be acquired through the newly acquired consumer due to network effects, and value will be also created in the form of tokens.

### Other ideas that have been discussed:

- Potential to add standardised metadata to articles, possibly starting with the gifted articles that could be bundled for our engaged users.
- The more engaged, your "badge" will go up, and your opinion should be more respected/listened among the community.
- Digital Asset: NFT - bluetick with metadata that will explain how loyal is that user. That will also give status to the user. Bring personalization to the badge: sporty user, or more into US politics, etc. Another badge could be “Donation”.
- What does read mean? % of the article / scrolling / time spent on it?
- Governance from community / voting.
- Language blockers.
- [Metadata standard](https://schema.org/)
- [Metadata service to build a persona](https://developer.ap.org/ap-metadata-services/) 
- Providing [open industry standards](https://openrtb.github.io/OpenRTB/) for communication between buyers of advertising and sellers of publisher inventory.
- Ad targeting based on what the user is more interested in - [Topics API project](https://github.com/patcg-individual-drafts/topics). 
- Metadata standards and examples:
  - [IPTC](https://iptc.org/) is the global standard body of the news media that provides the technical foundation for the news ecosystem.
  - [Reuters topic codes](https://liaison.reuters.com/tools/topic-codes). 
- There’s some work already done for decentralised IDs (DID):
  - [Basic spec](https://w3c.github.io/did-core/) followed by Polkadot.
  - [KILT approach](https://github.com/KILTprotocol/kilt-did-driver/blob/master/docs/did-spec/spec.md)
- Building community is key.
- Web3 is about composability - using what has already been built.

## Next steps

During the next sprint we will dive deeper into some key aspects of the solution: the account creation process, the publishing access, the concepts of DID and verifiable credentials, and the CMS integration in Web2.

| Number        | Workshop      | Date         | Duration     |
| ------------- | ------------- |------------- |------------- |
| 8.1 | Solution Tech Assessment (1/2) |28.11.2022 - 11.30PM CET|30min|
| 8.2 | Solution Tech Assessment (2/2) |01.12.2022 - 2PM CET|30min|
| 8.3 | Tech Architecture: Q&A  |02.12.2022 - 11AM CET|60min|
| 8.4 | First Architecture approach - review  |02.12.2022 - 4PM CET|60min|
