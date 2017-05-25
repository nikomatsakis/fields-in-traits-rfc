# fields-in-traits-rfc

An (experimental) RFC repo devoted to the "fields in traits" RFC. This repo is an effort to collect and organize the discussion around this RFC -- and possibly follow-up RFCs as well!  The idea is to focus on one RFC at a time, though, while collecting ideas that could make sense for follow-up work.

### Current RFC and overall vision

The main gist of the RFC is to allow fields in traits. These fields map into the memory locations in the implementing type. They are intentionally **not** fully general properties, for reasons outlined in the RFC.

However, if this works out, I'll probably use this repo to also organize some follow-up RFCs that fit loosely into [the "virtual struct" / "efficient inheritance" umbrella](https://github.com/rust-lang/rfcs/issues/349). Examples include upcasting between trait types, `#[repr]` on traits that permit more efficient object representation, etc.

### How the issues are organized

I've tried to setup a labeling scheme for issues to help people find stuff easily. I'm not sure if this is the best setup!

**Help-wanted.**

The `help wanted` label indicates issues where a PR would be most welcome. 

**Priority (the P labels).**

- `P-essential` means that we have to resolve this for the current RFC. It might be that this is better suited to a milestone. 
- `P-nice-to-have` means that it might be nice to include this in the RFC, but it might also be better left for follow-up work.
- `P-wild-and-crazy` means that these are far-out ideas that may or may not make sense.

**Resolution (the Z labels).**

Once an issue is closed, it ought to have a resolution tag.

- `Z-updated-rfc` -- text was added to the RFC resolving this question
- `Z-open-question` -- text was added to the RFC making this an "open question" to be resolved before stabilization
- `Z-alternative` -- text was added to the RFC describing this as an alternative but not endorsing it
- `Z-no-go` -- nothing was added to the RFC. This is out of scope or just something we decided against.
- `Z-duplicate` -- a duplicate of some other issue

