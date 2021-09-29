## __Fitst Repositor of EUNSOL__

---

#### __I want to learn the basic methods of using [GitHub](https://en.wikipedia.org/wiki/GitHub "Wikipedia's GitHub.") and the basics of [web programming](https://en.wikipedia.org/wiki/Outline_of_web_design_and_web_development "Outline of web design and web development").__

+ My hobby is computer game⚔ and reading a text.📃
+ I want to experience various knowledge related to _computers_.
+ I'm happy to open the _first_ Git Hub repository. I look forward to your kind cooperation!🤗


```Python
print('### Korean Population by Region')
print('* Total population:', sum_people)

print('| Region | Population | Ratio (%) |')
print('| ------ | ---------- | --------- |')
for idx, pop in enumerate(n_people):
    ratio = pop/sum_people*100 # TODO: The ratio of new cases to the total
    print('| %s | %d | %.1f |' % (regions[idx], pop, ratio))
print('')

print('### Korean COVID-19 New Cases by Region')
print('* Total new cases:', sum_covid)

print('| Region | New Cases | Ratio (%) | New Cases / 1M |')
print('| ------ | --------- | --------- | -------------- |')
for idx, pop in enumerate(n_covid):
    ratio = pop/sum_covid # TODO: The ratio of new cases to the total
    print('| %s | %d | %.1f | %.1f |' % (regions[idx], pop, ratio, norm_covid[idx]))
print('')
```
