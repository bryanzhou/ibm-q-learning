``` What does "quantum" mean? ```
* Quantum theory, developed in the early 1900’s, revolutionized physics and chemistry by successfully explaining the weird behavior of tiny particles like atoms and electrons.  In the late twentieth century it was discovered that it applied not just to these particles, but to information itself. This led to a revolution in the science and technology of information processing, making possible previously unimagined kinds of computing and communication.
* 量子理论，创立于20世纪初期，由于成功的解释了像原子和电子这样微观粒子的行为而革命性的改变了物理学和化学。在20世纪晚期，人们发现了量子理论不但适用于微观粒子，也适用于信息（我觉得指微观粒子上附带的信息）。这引起了信息处理相关的科学技术出现了新的变革，使原先无法想象的计算和数据传输方式有了新的可能。

``` What is a quantum computer? ```
* A quantum computer is a device able to manipulate delicate quantum states in a controlled fashion, the way an ordinary computer manipulates its bits.
* 量子计算机是一种能操作处于受控态微观粒子的设备，就像是传统计算机操作一个比特位。

``` What is a qubit? ```
* A qubit is the quantum version of a bit, and its quantum state can take values of |0>, |1>, or ***both at once***, a phenomenon known as ***superposition***.  The half angle bracket notation |>  is conventionally used to distinguish qubits from ordinary bits.
* 量子位（qubit）一种量子维度的比特位，它的量子状态可以取值为0，1或同时在两种状态（这一点也是区别于传统计算机比特位最大的区别），一种被称为叠加态的状态。|> 这个符号通常被用来区分传统比特位与量子位。

``` What is a superposition? ```
*  A superposition is a weighted sum or difference of two or more states; for example, the state of the air when two or more musical tones are sounding at once.  Ordinary, or “classical,” superpositions commonly occur in everyday phenomena involving waves.
* 叠加态是一种两个或多个状态的加权和或差。举个栗子，当空气中有两种以上音乐响起时空气的状态。（这里没说清楚，具体解释是，声音在空气中的传播是以波的形式，叠加态可以理解成两个或多个波叠加的情景。这种解释和实际的量子叠加还是稍有不同，下面这个会有解释）。传统物理上，“叠加”通常发生在“波”上。

``` How are quantum superpositions different? ```
* Quantum theory predicts that a computer with N qubits can exist in a superposition of all 2^N of its distinct logical states |00…0> through  |11…1>.  This is exponentially more than a classical superposition. Playing N musical tones at once can only produce a superposition of N states.
* 量子理论预言一个有N个量子位的计算机可以存在从|00…0> 到 |11…1>的 2^N 种不同叠加态。这比传统的叠加呈现几何级数的增加。同时演奏的N种音乐智能产生一个N个状态的叠加（与之相对的量子叠加是同时存在2^N个状态）。

``` How is a quantum superposition different from massive parallelism? ```
``` 量子叠加与大规模并行有何区别（可以理解成量子计算与大规模并行计算的区别） ```
* Though superposition is stronger than a probabilism, it is weaker than actually having an army of 2^N real computers all working on the problem at once. Superposition is strictly weaker than full parallelism, and strictly stronger than probabilism.
* 虽然叠加态是要强于盖然性的，但（N个量子位的量子计算机）还是弱于2^N的计算机个计算机处理同一个问题的。（这地方不太会翻译，总的意思就是N个量子位的量子计算机由于它的叠加态，是强于只能有1个确定状态的单机的，但是也还是不如2^N台机器进行并行计算。）

```What is entanglement?```
```什么是量子纠缠?```
* Entanglement is a property of most quantum superpositions and does not occur in classical superpositions. In an entangled state, the whole system is in a definite state, even though the parts are not. Observing one of two entangled particles makes it behave randomly, but tells the observer exactly how the other particle would act if a similar observation were made on it. Because entanglement involves a correlation between individually random behaviors of the two particles, it cannot be used to send a message. Therefore, the term “instantaneous action at a distance,” sometimes used to describe entanglement, is a misnomer. There is no action, only correlation, which, though uncannily perfect, can only be detected afterward when the two observers compare notes. The ability of quantum computers to exist in entangled states is responsible for much of their extra computing power, as well as many other feats of quantum information processing that cannot be performed, or even described, classically.
* 量子纠缠是大多数量子叠加态的一个属性，它并不会发生再传统物理的叠加现象中。在量子纠缠状态下，整个系统处于一个确定的状态，即使其部分不是。观察两个纠缠粒子中的一个，它的行为是随机的，但是它可以准确的告诉观察者如果以同样的方式去观察另一个粒子会有什么样的行为。因为纠缠涉及分开的两个粒子的随机行为之间的联系，它没法用来发送消息。因此，用“即使距离时（传递）的瞬间行为”来描述纠缠，是不恰当的。没有行为，只有联系，只能对比两个观测数据后发现，令人惊讶的完美。量子计算机在纠缠态中存在的能力，是它们额外的计算能力的主要原因，也是很多其他量子信息处理方式无法实现，甚至描述的壮举。

```What is a quantum gate?```
```什么是量子门?```
* Quantum gates are the elementary building blocks for quantum computation, acting on qubits the way classical logic gates act on bits, one and two at a time, to change their state in a controllable way.
* 量子门是量子计算的基本组成部分，对于量子位的其作用就像是（电）逻辑门对传统比特位的作用一样，可以以可控的方式改变量子位的状态。
