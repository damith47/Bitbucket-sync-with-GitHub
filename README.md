**Configuration steps**


1. GitHub, create a new repository (import or from scratch).


2. Bitbucket, Enable Pipelines under Repository settings > Pipelines > Settings and enable Pipelines.


3. Bitbucket, Generate keys under Repository settings > Pipelines > SSH keys. Copy the public key to clipboard.


4. the same page, under Known hosts enter github.com as the Host address and then click Fetch followed by Add host.


5. GitHub, add the public key under Settings > Security > Deploy keys > Add deploy key. Tick the checkbox to Allow write access.


6. Bitbucket, add the public key under Repository settings > Security > Access keys > Add key.
