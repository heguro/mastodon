# mstdn-timeline-server

A fork of [Mastodon](https://github.com/tootsuite/mastodon)

## Configure

After installation, add these lines to `.env.production`:

```plain
GITHUB_REPOSITORY=[github repo]
TLSVR_FOLLOWBOT0=[@0's account id]
TLSVR_FOLLOWBOT1=[@1's account id]
TLSVR_FOLLOWBOT2=[@2's account id]
TLSVR_FOLLOWBOT3=[@3's account id]
TLSVR_HASHTAG=[hashtag without #]
```

Example:

```plain
GITHUB_REPOSITORY=heguro/mstdn-timeline-server
TLSVR_FOLLOWBOT0=2
TLSVR_FOLLOWBOT1=3
TLSVR_FOLLOWBOT2=4
TLSVR_FOLLOWBOT3=5
TLSVR_HASHTAG=jptl
```

## License

Copyright (C) 2016-2020 Eugen Rochko & other Mastodon contributors (see [AUTHORS.md](AUTHORS.md))

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
