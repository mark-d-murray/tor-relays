# The Five Eyes


[The Five Eyes](https://en.wikipedia.org/wiki/Five_Eyes) (FVEY) is an intelligence alliance comprising Australia, Canada, New Zealand, the United Kingdom, and the United States. Former NSA contractor Edward Snowden revealed that the FVEY has been spying on one another's citizens and sharing the collected information with each other in order to circumvent restrictive domestic regulations on surveillance of citizens.

If you are using Tor to browse the internet, you can prevent it from using any relay in the Five Eyes by adding the following to your torrc

```text
ExcludeNodes {au},{ca},{nz},{gb},{us}
StrictNodes 1
```

# The Fourteen Eyes

According to Snowden, there is a similar working agreement between the Five Eyes and other countries, known as Fourteen Eyes or SSEUR. The full list of the Fourteen Eyes is Australia, Canada, New Zealand, Great Britain, United States, Denmark, France, Netherlands, Norway, Belgium, Germany, Italy, Spain, and Sweden.

You can use a similar entry in your torrc file to prevent Tor connecting to any of the Fourteen Eyes

```text
ExcludeNodes {au},{ca},{nz},{gb},{us},{dk},{fr},{nl},{no},{be},{de},{it},{es},{se}
StrictNodes 1
```
