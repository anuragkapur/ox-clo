# Cloud Computing Background

## Amdahl's Law

For a fixed amount of work, the speedup is limited by the time taken to complete the part of the program that can't be
serialised.

![Amdahl's Law - speedup](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/AmdahlsLaw.svg/800px-AmdahlsLaw.svg.png)

## Gustafson's Law

As computing power increases, more work can be done in a fixed amount of time.

![Gustafson's Law - speedup](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Gustafson.png/800px-Gustafson.png)

## Comparing Amdahl's and Gustafson's Law

Ref: A driving metaphor from course slides

* Amdahl’s Law
– You are travelling to London (60 miles) –  30 miles in you have spent one hour
– You can never average > 60 mph
* Gustafson’s Law
– You are travelling across the US
– You’ve spent an hour at 30 mph
– You can achieve any average speed given enough time and distance

## ACID

* Atomicity - all or nothing
* Consistency - a transaction always leaves the system in a valid state; invariants are always satisfied
* Isolation - single user behaviour consistent with multi user behaviour
* Durability - permanent committed results

## CAP Theorem

* Consistency - every read receives the most recent write or an error; not same as Consistency in ACID context.
* Availability - every request receives a response, without any guarantees that it is the most recent version of info
* Partitioned - system can tolerate failures

* CA - traditional RDBMS
* AP - NoSQL databases
* CP - not a good idea

## References

* https://en.wikipedia.org/wiki/Amdahl%27s_law
* https://en.wikipedia.org/wiki/Gustafson%27s_law
