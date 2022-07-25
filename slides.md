class: middle, center

# A case study about Comparative Programming Languages' Energy Consumption

Aleksander Lisiecki

.right[AlekLisiecki @ Twitter]
.right[aleklisi @ GitHub]
.right[aleksander.lisiecki@erlang-solutions.com]

---
# **Where** does electrical energy consumption matter?

 - IoT
 - Electric cars
 - Smartphones and laptops
 - Spacecrafts, satellites, probes
 - ...

---

.scale60[![running android studio](images/running_android_studio.jpeg)]
[1]

---
# But not only there...

"Last year, Google used about **12.4 terawatt-hours** of electricity, which means it uses more electric power than entire countries, including ones like Sri Lanka and Zambia." [2] the article is form 2020

Total electricity used by Meta (Facebook) in 2020 was **7,170,000 MWh**. [3]

Total electricity used by Microsoft in 2019 was **8,741,807 MWh**. [4]

"In 2020, the average annual electricity consumption for a U.S. residential utility customer was 10,715 kilowatthours (kWh)[...]" [5]

| Company | energy used in kWh | Residential utilities equivalent |
|--:-|---:|---:|
| Google | 12,400,000,000 | 1,157,256 |
| Microsoft | 8,741,807,000 | 815,847 |
| Meta(Facebook) | 7,170,000,000 | 669,155 |

---
# **Why** does it matter?

.scale45[![Bitcoin Coal power plan](images/bitcoin_mining_coal.png)]
.scale45[![Paying bills](images/paying-bills.jpeg)]
[7] [8]

---
class: middle, center
# What should we do to save the electrical energy?

---
# We could give up electricity completely

.scale80[![Amish](images/amish.jpeg)]

[9]

---
class: middle, center
# We could use energy efficient technologies

---
# What is electrical current?

"An **electric current** is a stream of charged particles, such as electrons or ions, moving through an electrical conductor or space." [10]

.scale45[![Light bulb](images/light_bulb_and_a_batery.jpeg)]
.scale45[![Thunder](images/thunder.webp)]

[11] [12]

---
# What is electrical current? (for common people)
.scale60[![Ohm's law](images/Ohms-law-cartoon-cropped.jpeg)]

[13]

---
# Power

"**Electric power** is the rate, per unit time, at which electrical energy is transferred by an electric circuit." [14]

P = V * I

where:
- P is electric power in watts [W]
- I is electric current in amperes [A]
- V is electric potential or voltage in volts [V]

---
# Energy

"**Electrical energy** is energy derived as a result of movement of electrically charged particles. When used loosely, electrical energy refers to energy that has been converted from electric potential energy." [15]

E = P * t

where:
- E is electrical energy in jules [J]*
- P is electric power in watts [W]
- t is time [s]

*"Electrical energy is usually sold by the kilowatt hour (1 kW·h = 3.6 MJ) which is the product of the power in kilowatts multiplied by running time in hours."[15]

*I promise this is as hard as it gets with the maths in this talk!*

---
# From theory ...

.scale90[![test setup](images/test_setup.png)]

---
# ... to practice

.scale45[![mess1](images/wires_mess_on_table.jpeg)]
.scale45[![mess2](images/computers_setup.jpeg)]

---
class: middle, center

# Thank you for your attention
