# Bakalárska práca - návrh prevádzky smarthome

## Abstrakt
Táto bakalárska práca sa zaoberá návrhom prevádzky inteligentnej domácnosti s využitím IoT technológií a platformy Home Assistant. Cieľom práce je vytvoriť efektívne a cenovo dostupné riešenie, ktoré zabezpečuje monitorovanie a riadenie rôznych aspektov domáceho prostredia s ohľadom na komfort a energetickú úsporu.
V rámci práce sa najprv analyzujú základné pojmy inteligentných domácností a Internetu vecí (IoT), ktoré tvoria teoretický základ pre ďalšie kroky návrhu. Súčasne je preskúmaný komunikačný protokol MQTT a jeho výhody v kontexte inteligentných domácností.
Praktická časť práce zahŕňa výber a implementáciu senzorov DS18B20, DHT11 a BM1750 pre meranie teploty, vlhkosti a osvetlenia. Tieto senzory sú integrované do mikrokontroléra ESP32, ktorý využíva MQTT protokol na komunikáciu s platformou Home Assistant. Implementácia sa realizuje pomocou vývojového prostredia Visual Studio Code (VScode) s rozšírením PlatformIO, ktoré poskytuje vývojové a programovacie prostriedky pre ESP32.
Ďalším krokom je konfigurácia a automatizácia systému pomocou nástroja Node-RED, ktorý umožňuje vytvárať vizuálne založené toky dát a automatizačné scenáre. Systém je schopný monitorovať a ovládať teplotu, vlhkosť a osvetlenie prostredníctvom senzorov a poskytuje možnosti prispôsobenia a ovládania prostredníctvom aplikácie Home Assistant.
Výsledky práce zahŕňajú funkčný návrh a implementáciu inteligentnej domácnosti, ktorá zabezpečuje pohodlie a energetickú úsporu. Účinnosť systému je overená experimentálnymi meraniami a testovaním v reálnom prostredí.
V závere práce sa diskutuje o možnostiach ďalšieho rozvoja a aplikácií návrhu, ako aj jeho prínose pre súčasné aj budúce domácnosti. Práca prináša príklad implementácie inteligentnej domácnosti s dôrazom na efektivitu, pohodlie a úsporu energie, a poskytuje platformu pre ďalšie rozšírenie a vylepšenie v tejto oblasti.

