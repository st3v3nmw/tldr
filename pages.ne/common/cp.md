# cp

> फाइलहरू र डिरेक्टोरीहरू सार्नुहोस।
> थप जानकारी: <https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html>।

- एउटा स्थान बाट अर्को स्थानमा फाइलहरु सार्नुहोस:

`cp {{स्रोत_फाइल.ext/को/पथ}} {{लक्ष्य_फाइल.ext/को/पथ}}`

- फाइलको नाम उही राखेर अर्को डिरेक्टोरीमा फाइलहरु सार्नुहोस:

`cp {{स्रोत_फाइल.ext/को/पथ}} {{लक्षित_अभिभावक_निर्देशिका/को/पथ}}`

- पुनरावर्ती रूपमा डिरेक्टोरीमा भएका सबै चीजहरुलाइ अर्को स्थानमा सार्नुहोस(यदि स्थान पहिले देखि नै छ भने,डिरेक्टोरी भित्र सार्नुहोस):

`cp -R {{स्रोत_निर्देशिका/को/पथ}} {{लक्ष्य_निर्देशिका/को/पथ}}`

- पुनरावर्ती रूपमा एउटा डाइरेक्टरी सार्नुहोस, शब्दमय रुपमा (फाइलहरु सार्दा सार्दै सरिरहेको पनि देखिन्छ):

`cp -vR {{स्रोत_निर्देशिका/को/पथ}} {{लक्ष्य_निर्देशिका/को/पथ}}`

- अन्तरक्रियात्मक रुपमा अर्को स्थानमा पाठ्य फाइलहरू सार्नुहोस (अधिलेखन गर्नु अघि प्रयोगकर्तालाई सोध्छ):

`cp -i {{*.txt}} {{लक्ष्य_निर्देशिका/को/पथ}}`

- सार्नु अघि प्रतीकात्मक लिङ्कहरू पछ्याउनुहोस्:

`cp -L {{लिङ्क}} {{लक्ष्य_निर्देशिका/को/पथ}}`
