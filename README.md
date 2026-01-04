# United States State Flags

This repo is a public resource for artists and developers.

## Structure

### `/flags`

Contains 56 folders (one per flag) using 2-letter lowercase abbreviations:

- 50 US states (al, ak, az, ... wy)
- District of Columbia (dc)
- 5 territories (as, gu, mp, pr, vi)

Each folder contains:

```
{state}/
  {state}.svg            # Original vector file
  {state}_48x32.png      # Icon size
  {state}_120x80.png     # Small
  {state}_240x160.png    # Thumbnail
  {state}_480x320.png    # Medium
  {state}_960x640.png    # Large
```

All PNG files have:

- Transparent backgrounds
- Fixed dimensions (consistent across all flags)
- Proportionally scaled flags centered within canvas

## State Abbreviations

| State         | Code |     | State          | Code |
| ------------- | ---- | --- | -------------- | ---- |
| Alabama       | al   |     | Montana        | mt   |
| Alaska        | ak   |     | Nebraska       | ne   |
| Arizona       | az   |     | Nevada         | nv   |
| Arkansas      | ar   |     | New Hampshire  | nh   |
| California    | ca   |     | New Jersey     | nj   |
| Colorado      | co   |     | New Mexico     | nm   |
| Connecticut   | ct   |     | New York       | ny   |
| Delaware      | de   |     | North Carolina | nc   |
| Florida       | fl   |     | North Dakota   | nd   |
| Georgia       | ga   |     | Ohio           | oh   |
| Hawaii        | hi   |     | Oklahoma       | ok   |
| Idaho         | id   |     | Oregon         | or   |
| Illinois      | il   |     | Pennsylvania   | pa   |
| Indiana       | in   |     | Rhode Island   | ri   |
| Iowa          | ia   |     | South Carolina | sc   |
| Kansas        | ks   |     | South Dakota   | sd   |
| Kentucky      | ky   |     | Tennessee      | tn   |
| Louisiana     | la   |     | Texas          | tx   |
| Maine         | me   |     | Utah           | ut   |
| Maryland      | md   |     | Vermont        | vt   |
| Massachusetts | ma   |     | Virginia       | va   |
| Michigan      | mi   |     | Washington     | wa   |
| Minnesota     | mn   |     | West Virginia  | wv   |
| Mississippi   | ms   |     | Wisconsin      | wi   |
| Missouri      | mo   |     | Wyoming        | wy   |

### Territories & District

| Territory                | Code |
| ------------------------ | ---- |
| American Samoa           | as   |
| District of Columbia     | dc   |
| Guam                     | gu   |
| Northern Mariana Islands | mp   |
| Puerto Rico              | pr   |
| U.S. Virgin Islands      | vi   |

## Source

Original SVG images pulled from public domain on 10/11/2019: https://en.wikipedia.org/wiki/Flags_of_the_U.S._states_and_territories

See also: https://github.com/oxguy3/flags/tree/master/svg for a comprehensive collection of state and international flags.
