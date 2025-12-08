# data

The dataset contains `r nrow(squirrels)` observations and `r ncol(squirrels)` variables. 

## squirrels

- `X`: Indicates the longitude coordinate for an observed squirrel.
- `Y`:  Indicates the latitude coordinate for an observed squirrel.
- `Unique Squirrel ID`: Each squirrel was given a unique identifier to distinguish them from each other. This variable consists of these identifiers.
- `Hectare`: The census divided the park into about 350 one-hectare sections. This indicates which hectare the squirrel was observed within.
- `Shift`: The census was conducted by volunteers in AM and PM shifts. This variable notes if the squirrel was observed in the AM or PM.
- `Date`: This variable notes the date that the squirrel was observed in the following monthdayyear format: 01012001
- `Hectare Squirrel Number`: Describes the number in the chronological order of squirrel sightings within the hectare that the squirrel was observed in.
- `Age` Adult/Juvenile, Describes the perceived age of a squirrel based on its appearance to the observer.
- `Primary Fur Color`: The dominating color of the observed squirrel's fur.
- `Highlight Fur Color`: The secondary color of the observed squirrel's fur.
- `Combination of Primary and Highlight Color`: The dominating color of the observed squirrel's fur and the secondary color of the observed squirrel's fur.
- `Color Notes`: Variable accounts for additonal notes about the squirrel's appearance left by the observer.
- `Location` : Above Ground/Ground Plane, indicates whether the squirrel was observed on the ground or above the ground.
- `Above Ground Sighter Measurement`: Variable indicated the height, in feet, that a squirrel was observed off of the ground.
- `Specific Location`: Variable accounts for notes by participants recording the specific location of a squirrel, like on a tree branch, or on a bench.
- `Running`: TRUE/FALSE, indicates whether the observed squirrel was running. TRUE indicates it was. False indicates it was not.
- `Chasing`: TRUE/FALSE, indicates whether the observed squirrel was chasing something. TRUE indicates it was. False indicates it was not.
- `Climbing`: TRUE/FALSE, indicates whether the observed squirrel was climbing. TRUE indicates it was. False indicates it was not.
- `Eating` : TRUE/FALSE, indicates whether the observed squirrel was eating. TRUE indicates it was. False indicates it was not.
- `Foraging`: TRUE/FALSE, indicates whether the observed squirrel was looking for food. TRUE indicates it was. False indicates it was not.
- `Other Activities` Variable consists of additional activities of observed squirrel that were noted by participants.
- `Kuks`: TRUE/FALSE, indicates whether the observed squirrel was making a Kuk sound, a vocalization associated with alarm in squirrels. TRUE indicates it was. False indicates it was not.
- `Quaas`: TRUE/FALSE, indicates whether the observed squirrel was making a Quaa sound, a vocalization associated with the removal of a threat in squirrels. TRUE indicates it was. False indicates it was not.
- `Moans`: TRUE/FALSE, indicates whether the observed squirrel was making a Moan sound, a vocalization associated with the presence of an unclear threat in squirrels. TRUE indicates it was. False indicates it was not.
- `Tail flags` : TRUE/FALSE, indicates whether the observed squirrel was flagging its tail, a motion used to signal alarm. TRUE indicates it was. False indicates it was not.
- `Tail twitches`: TRUE/FALSE, indicates whether the observed the squirrel's flag was twitching. TRUE indicates it was. False indicates it was not.
- `Approaches`: TRUE/FALSE, indicates whether the observed squirrel was approaching the observer. TRUE indicates it was. False indicates it was not.
- `Indifferent`: TRUE/FALSE, indicates whether the observed squirrel was behaving indifferently towards the observer. TRUE indicates it was. False indicates it was not.
- `Runs from`: TRUE/FALSE, indicates whether the observed squirrel was running away from the observer. TRUE indicates it was. False indicates it was not.
- `Other interactions`: Variable consists of additional interactions between observers and the observed squirrel that were noted by participants.
- `Lat/Long`: Indicates the coordinate points where the squirrel was observed.
