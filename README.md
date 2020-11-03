# Frame Development

Components
1. Node Template
2. Front End Template

Add a Custom struct Referendum in template module and interact with it using pallet interactor.

Struct

```
pub struct Referendum{
	voter: Vec<u8>,
	refname: Vec<u8>,
	vote: Vec<u8>,
}

```

<img src='https://github.com/rafat/framedev/blob/main/img/doreferendum.jpg' />

Name, Proposition and Comment map to voter, refname and vote keys of the struct Referendum.

Querying the saved struct values.

<img src='https://github.com/rafat/framedev/blob/main/img/votestatus.jpg' />
