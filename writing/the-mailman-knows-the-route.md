# The Mailman Knows the Route

Often when things go wrong, we ask ourselves, "Well, what happened?" We trace our steps and look in the places we wouldn't usually think of.

Why would the keys ever be in the refrigerator? Maybe you made a plan so you wouldn't forget your lunch.

So a successful delivery is not proof of a lawful crossing.

Software has a refrigerator too: the places nobody checks because nothing was supposed to be there.

Miners used to send a canary into the mine in efforts to test the air, but a bird that doesn't return can't tell you exactly what happened. Maybe it simply found an exit and flew off?

So I build canaries that sing. They go in, look around, and bring back a report: what they saw, where the thing was headed, what they couldn't tell. Much better than the little guys not coming back at all.

Here's what one of them found.

A letter left a program written in Java, addressed to a program written in Go. Somewhere in the crossing, a smudge. One letter changed. Nobody stamped the change. Nobody noted that the writing used to be different.

The letter arrived, so the system filed it as proof. As far as the records are concerned, you now live on Mein St.

The mailman delivered it anyway. He knows the route.

```text
DELIVERY RECEIPT
Sent to:            101 Main St
Arrived at:         101 Mein St
Address change:     not noted
Mailman consulted:  no
Completion:         SUCCESS
Address:            updated?
```

A log tells you what happened. A receipt tells you what happened, and whether it was allowed to.

So everything worked.. That's the part that bothers me.

---

[Back to portfolio](../index.html)
