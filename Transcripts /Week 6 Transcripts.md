Module 6 Lecture 31: - The Central Limit Theorem and its Applications - Part 01
Transcript
0:17
In the last class, before I ended, I talked about the essential problem of any measurement
0:26
process. The problem is that, there is ahh objective
0:34
value out there. It can be the mass of an electron which you
0:39
are trying to measure. An objective value is there and we are trying
0:43
to measure it by certain number of experimental runs.
0:47
Or a situation where a biologist has discovered a new type of insect, and has to specify that
0:57
by measuring the body weight, average body weight.
1:00
Now, there is an average body weight of that particular insect ‘out there’— objective
1:08
value — but we are trying to measure it and obviously, if we can really collect all
1:14
the members of that species, and measure them, and take the average, it will be the right
1:21
value. So, there is an objective value.
1:25
But always we are able to collect a smaller number of samples from that species, and measure
1:34
it, and from there we are trying to infer something about the whole species.
1:40
In case of a physics measurement also, if we can run the experiment a million times,
1:47
maybe ah infinite number of times, then we will get the the
1:52
the mean value as the mass of the electron, but it is not possible to do so.
1:56
We always collect samples. That means, whenever we are doing, say, 10
2:03
experimental runs, getting 10 values, and obtaining the mean of that, we are essentially
2:09
sampling for from an infinitely many possible number of readings.
2:16
We are sampling. So, both in case of a physics measurement
2:22
as well as in case of a biology measurement there is the... there is the issue of of sampling.
2:31
But then the the the essential question is that,
2:35
how many... how large should be the sample, so that you can be fairly certain, fairly
2:43
confident when you are stating the result? And then, if you have taken, say, a 10 readings
2:55
and obtained a mean value. If you now take another 10 readings and obtain
3:02
another mean value, again you repeat that experiment by taking another 10 readings and
3:08
obtaining a mean value, all those mean values will not be the same.
3:11
And therefore, the question comes: which value do you state as your measured value and how
3:21
reliable will that measured value be for a third person?
3:26
And since experiments necessarily need to be repeatable-reproducible and therefore,
3:32
we have to state it in a form, so that it can be reproduced by anybody anywhere else
3:38
in the world. So, that’s another issue.
3:44
So, you might want to to specify a range within which the actual value... you are fairly confident
3:53
that it will lie in that range. But how do you specify that range?
3:59
You are, after all, taking a finite number of measurements.
4:03
And if you do specify a range then with what level of confidence are you specifying that
4:12
range? These are the natural questions that come
4:14
whenever you are making any measurement. So, the effective point is that, there is
4:20
a a... I would say population mean, mean 𝞵, and a population standard deviation
4:41
𝞼. These are, these are out, say ‘out there’,
4:50
existing. Existing, and we are trying to measure that.
4:58
But what we actually have in hand are this sample mean, we had called it x̿.
5:11
And the sample standard deviation, we have to call it 𝙨.
5:19
And this is something that we have in hand.
5:28
And we... we are trying to make some kind of a confident assessment of these using these.
5:37
How do we do that? So, that is the question we are now facing.
5:44
So, we always take samples, and we have the sample mean and the sample standard deviation
5:51
in hand. There is another issue.
5:55
the issue is that the distribution of values in a population need not always be a normal
6:03
distribution. For example, if you are talking about a particular
6:08
species of organisms and you are talking about their average weight, then the distribution
6:15
of weights might not be a normal distribution. It will depend on the character of the species.
6:22
It might be something like this. It might be something like this.
6:35
That means, it might peak at some place, there would be nothing, no organism, found in a
6:45
particular weight, and all that are possible. But still we would like to obtain some kind
6:56
of a handle on the population mean and the population standard deviation using the sample
7:02
mean and the sample standard deviation. Now consider the issue: Suppose I have taken
7:11
10 of these samples and have obtained the sample mean and the sample standard deviation.
7:19
Then I might get something, say, a value here, the mean is here.
7:26
But the individuals would be extract... would be distributed all over the place.
7:33
That means, one individual may have this value of the weight, another individual may have
7:37
this value of the weight, another, all that taken together when you take the mean, it
7:41
would be somewhere here. So, the mean value we have got here.
7:47
Suppose you take another 10 samples and again obtain the mean, it will again have the individual,
7:56
distributed all over the place, but the mean will come somewhere close here.
8:00
And again if you do the same experiment, collecting another 10 samples, you will... it will again
8:06
come somewhere close here, but not exactly the same.
8:08
It will be distributed in some way. What kind of distribution will that be?
8:20
In case of the population it can have its own inherent species-specific distribution.
8:28
Or, for example, if you are a geologist trying to measure the average density of the Earths
8:38
crust, then you might collect samples from various places.
8:41
In some place the sample might be more dense, in some place it might be less dense.
8:46
So, it will have a distribution. The distribution, characteristic of the material
8:51
with which the earth’s crust is formed. But every time you make the measurement, that
8:57
means, take sample from different places, take the average, you will get a value.
9:02
And every time you repeat that process you will get every time slightly different values.
9:08
The question is that, if I now talk about how will the means be distributed?
9:14
What will be the distribution like? In case of the measurement of the mass of
9:20
an electron, every time you measure, you will get a different value.
9:23
Can’t help it. There will be some fluctuations from the normal
9:28
value due to various random errors. So, there will be different values.
9:34
And suppose you take 10 measurements and you take the average.
9:37
You get a value. Again you make another 10 measurements, take
9:40
the average, you will get a value. And keep on repeating that, you will get a
9:44
distribution of the mean values. What distribution will it be?
9:50
Now, there is a theorem in statistics that asserts that, if the the number of samples
10:01
is bigger than a certain minimum number, then that distribution of the means will always
10:09
converge on to a Gaussian distribution, normal distribution.
10:14
Okay? Let me state the theorem;
10:17
let me state the theorem; Let me delete this and use the space here.
10:26
It’s called central limit theorem. It asserts that the the distribution of the
10:46
means will be a normal distribution. It says that for large sample size, the sampling
11:06
distribution, distribution of the mean, for samples
11:33
of size 𝙣 from a population, from a population with mean 𝞵 and standard deviation, standard
12:02
deviation 𝞼, may be approximated by a normal distribution distribution.
12:34
Then if I say, it’s a normal distribution, I have to specify its mean and standard deviation
12:40
with mean; the same mean as the population mean 𝞵.
12:47
And standard deviation... now this will be 𝞼, the population standard deviation, by
12:55
square root of n. This is the statement of the theorem.
12:59
Now, let us try to understand what it means. It means that, it says that
13:06
if I repeatedly conduct the experiment, each experiment comprises taking a number of samples
13:14
and then obtaining the mean, then if we do that repeatedly and talk about the distribution
13:22
of the means, the mean will... means will be distributed as a normal distribution.
13:32
It will be distributed as a normal distribution like this
13:41
with the mean at 𝞵 and this standard deviation, if the population standard deviation was 𝞼,
13:52
then the standard deviation would be sigma divided by square root of n.
13:58
Therefore, it depends on the number of samples we take.
14:04
Stands to reason. The point is that, if instead of 10 samples
14:11
I had taken 50 samples, it is... it will stand to reason that I will get a more accurate
14:18
estimate of the mean or the population mean.
14:21
More accurate estimate essentially means that its deviation from the population mean will
14:27
be small. Now, if I keep on repeating that experiment
14:33
a number of times, each time I will get a value that will be very close to the population
14:38
mean mu. And therefore, it will be a normal distribution,
14:42
but the normal distribution will have a lesser spread, which means that a lesser standard
14:50
deviation. So, the assertion is that the variance will
14:55
be inversely proportional... the variance
15:05
will be inversely proportional to 𝙣. And so, or variance will be... I will, I will
15:18
better right it this way... variance will be, this assertion is that...
15:27
It will be the variance of the population divided by 𝙣, inversely proportional to
15:34
𝙣, and therefore, this gives the standard deviation is the population standard deviation
15:41
divided by square root of n. Stands to reason.
15:47
Because if you take more, larger number of samples,
15:50
it will be more or more accurate representation, or more closely resemble the population mean
15:59
value, and therefore, the spread of that normal distribution
16:02
will be less. And it asser... this theorem asserts the variance
16:06
will be inversely proportional to the number of samples you take, and therefore, the standard
16:11
deviation would be 𝞼/√𝙣 [𝞼 by root 𝙣].
16:14
So, that is the assertion of the central limit theorem, what does it give us?
16:20
Actually the central limit theorem allows us to make a confident... or at least estimate,
16:28
the confidence with which we can state a value as the measured value.
16:35
That means if I state something as a measured value, I need to give some kind of a bound
16:41
and I need to talk about with what kind of confidence I am talking about that.
16:46
All that can be obtained using the central limit theorem.
16:49
I will illustrate
16:52
but I will illustrate that with the help of an example.
Module 6 Lecture 32: - The Central Limit Theorem and its Applications - Part 02
Transcript
0:08
The most important statement of the central limit
0:21
theorem is the fact that, it will slowly become a normal distribution.
0:28
Now, when you say a large sample size, what large, how large should it be?
0:36
Now, you can do this experiment numerically. Take a very badly skewed distribution; for
0:44
example, something like this. If you take a very bad distribution something
0:49
like this, a distribution like this as bad as this, there can be some samples here, nothing
1:01
here, some sample is there, nothing else. So, even for that bad distribution, if you
1:08
take 10 samples and obtain the mean, it will be somewhere here, if you take another 10
1:14
samples it will be somewhere around here, it will be another 10 sample will be somewhere here. So, all that you will get some distribution,
1:21
but it might not be a very good approximation to a normal distribution.
1:27
But if you take... instead, if you increase the number of samples each time, you will find that as you exceed say 20, it is more and more resembling a normal
1:37
distribution, and beyond 25, it is practically a normal distribution.
1:42
And because of that, you we normally take it for granted that beyond 25 if you take
1:49
further readings, it does not improve the approximation to a normal distribution.
1:55
So, it suffices to take 25 as the number. So, ‘large’ essentially means n should
2:04
be greater than or equal to 25, at least 25. And I would strongly advise you to do this
2:14
experiment numerically once, by taking random samples from this kind of a distribution,
2:20
and obtaining the mean, and finding how the means will be distributed. You will find that it approximates a normal distribution at as n exceeds 20,
2:32
and after 25 there is no further, no significant improvement in the approximation.
2:38
So, how large? 25. Okay? Now, on that basis, let us let us do a a an
2:49
an example. With the help of that, you will realize the advantage of the central limit theorem. Example: Suppose there is a population
3:23
population with mean 2; I will not specify 2 in units, because it could be any unit.
3:41
If you are measuring the height of a population it will be in meters, if you measure the weight of a population it will be in in kilograms. So, whatever it is, this is I I will
3:50
I will specify that as a unit independent number, and standard deviation, 0.7.
4:00
The distribution within this population is unknown.
4:09
Suppose you do not know that. Now, suppose
4:18
you take 20 samples out of that, out of that population and
4:35
and then you, you take 20 samples out of the population. And we are trying to assess what will be the probability...
4:47
So, what will be the probability that the sample mean will lie beyond, say, it was 2,
5:17
so let it be 2.2. So, as bad as this.
5:22
So, how do you proceed to to to attack a problem like this?
5:29
It says that the population has mean this, standard deviation this.
5:36
So, if you taken 20 samples you get some x̿, sample mean.
5:46
If you again take another 20 samples you will get a different x̿, the sample mean.
5:52
And if you keep on taking such 20 samples again and again, you will get a distribution
5:58
of the means and the the central limit theorem asserts, says that, since 20 is close to the
6:20
the necessary number 25, that it can be, it can be approximated by a normal distribution.
6:27
It can be approximated by a normal distribution with mean same as the population mean 2,
6:39
and standard deviation will be the population standard deviation 0.7 divided by square root
6:50
of the number of samples, you have taken, 20.
6:57
Okay? This comes to be 0.156.
7:04
So, that will be the standard deviation of the distribution of the means.
7:14
Now, we have to face the question: let me get some space yeah.
7:22
Now, we have to face the question: what will be the probability... let me write here; probability
7:34
P that x̿ lies above 2.2? This is question asked.
7:50
This is equal to probability that x̿ lies above—lies lies, I will I will write it
8:01
a bit differently—2.2, how different is it from the mean 2?
8:10
This is 0.2. Divide it by the standard deviation, which
8:16
is 0.156. This many is equal to it will become 1.28
8:27
standard divisions. I will not write S, this many standard deviations
8:34
above the mean. So, one point, 0.156 is the standard deviation,
8:55
and 1.28 standard deviations would be somewhere here. We are actually trying to find out. So, this is 1.28 standard deviation and we
9:09
are trying to find out the area under the curve in this range. This is what we have to find out. Now, the this value, the multiplier of the
9:26
standard deviation, is called the z value. In Americans, American pronunciation it will
9:32
be zee value, but let me go by the British pronunciation or Indian pronunciation: the
9:38
z value. The z value is the multiplier of this.
9:43
Now, people have integrated the normal distribution curve up to certain values and have tabulated
9:52
that. That is available as the z table and we have to read off the value from there. Let us do that.
10:03
Here I have plotted the z table and this is the normal distribution and here is the z
10:13
value. And what the z table gives is that, the area
10:18
under the whole curve is 1 and how much of that is contained to the left of that z value.
10:25
So, that is what gives the... what is given in the table. So, now, we have to read off the table the area to the left of 1.28, which is the z value.
10:38
So, when we do that, 1.2 is here and if we go further to the right, and 0.08 is here.
10:49
So, we get 0.8997 as the value; 0.8997 as the value, that we have to use.
11:02
And I will go ahead with that value to the rest of the calculation. So, let me write it afresh. A probability of x̿ lies 1.28 standard deviation
11:23
above the mean, this is what we needed to calculate.
11:35
And we have found that that value is; well let me; let me plot it once.
11:47
It is is a normal distribution because the number of samples was close to 25, 20 it was.
11:53
And here we know that this value is the population mean, which was 2.
12:06
The standard deviation was one point, one point, sorry 0.156, 0.156 and divided by square
12:28
root of n was 1.28. So, we had to calculate the area here, but
12:36
we have actually calculated the area to the left of that. So, this area; this area has turned out to be 0.8997.
12:51
So, this area will be 1 minus 0.8997 is equal to...
13:02
It will be 0.1003 which is... approximately this is about 10.03% 10% approximately,
13:16
which means that for the problem given, the actual the mean of the population was 2, but
13:28
by calculating, by obtaining 20 samples, I stand a chance about 10 percent chance of
13:36
obtaining a mean which is two point above 2.2. So, there is a high risk of committing ah error by making the measurement that way.
13:49
But suppose we increase the number of samples to 50 to sample...
13:56
Suppose we increase the number to 50. Then what happens? Then we get this curve, a a more narrower distribution.
14:09
It will become a narrower distribution, sorry... It will become a narrower distribution, and
14:26
in this narrow distribution the mean will be 2, the standard deviation will be; will
14:34
be 0.7 the original standard deviation, divide by root over 50.
14:41
Now, this is equal to 0.099. And, using this if we calculate, if you obtain
14:58
the z value. Then the z value will become: z is equal to,
15:07
the way we calculated, 2.2 minus the mean 2 divided by the new standard deviation which
15:15
is 0.099, then it comes to be about 2.02. And for this value if we again refer to the
15:27
z table, and then we find that the area under... the area to the left of the curve of of the
15:43
z value, in this case becomes 0.9783. Therefore, the probability of x̿ lies above
16:06
2.2 will now become 1 minus 0.9783, is equal to a small number, it will come to be 0.0217.
16:22
So, around 2 percent, 2.17 percent. So, the chance of committing an error will
16:28
be less. And notice that, all these we are being able
16:34
to calculate because the central limit theory asserts that the curve ultimately we get for
16:42
the distribution of the means will be a normal distribution. So, all this could be calculated using that fact.
16:51
Now, the value that we get... The value that we get by dividing by square
17:01
root of the n, that standard deviation of the sample means, is called the ‘standard
17:08
error of the mean’. Okay? So, this is a important thing that we get. A standard error error of the mean is, let
17:31
us call it, call it 𝞂. But, sigma of what? Of x̿, that is our 𝞂 divided by √𝙣. This is the standard error of the mean and
17:47
this gives an estimate of how much error can we commit by actually obtaining samples and
17:55
talking about the means obtained from the samples.
18:00
Let us illustrate that again with another example.
18:07
Now, another example: Suppose, you have measured some quantity 36 times...
18:24
I am using a square number so that it can be... you can obtain square root easily...
18:35
times, and have obtained obtain a sample mean, we are calling it x’[x-dash], you have got
19:04
it 112. This and a sample standard deviation, how
19:14
much is it? ‘s’ equal to 40.
19:21
Now the question is, what is the probability that the actual mean, the population mean,
19:42
we called it 𝞵, lies in the range, the range is given between 100 and 124.
20:03
100 is this mean minus 12 and 124 is this mean plus 12.
20:10
So, this is how we have defined the problem. So, notice that, in this case we have the
20:16
only the result of the sample available to us, and we do not know the actual population
20:22
mean or population standard deviation. In that case can we estimate some range in
20:28
which the population mean will lie and with which probability will that happen?
20:35
So, notice again the line of argument. If we repeated the argument, repeated the
20:43
experiment again and again, every time taking 36 samples,
20:49
then we will get... since 36 is bigger than 25... we will get a normal distribution of
20:55
the sample means. So, the sample means will have a normal distribution
21:00
something like this. So, this is the the mean of the...
21:15
not of the sample, but of the population, and it will have a standard deviation which
21:25
is the population standard division divided by root over 36, is 6.
21:32
So, this is what we can infer using this standard, the the central limit theorem.
21:43
Now, what we are trying to find out is the probability that the actual mean 𝞵 lies
21:52
in this range. Okay? So, so, probability of 𝞵 lies in the range: this is 100 to... 100 means actual x̿...
22:19
minus 12 to x̿ plus 12. This is what we are trying to find out.
22:32
Okay? Now this distribution we do not know really,
22:40
but we we have to try to somehow obtain the z value.
22:45
And for that, we need to find out the distribution the the standard deviation of this distribution.
22:51
But we do not know this number; this number is ‘out there’. This number is of the population, we have measured only the sample.
23:00
But the best we can do under the situation is to use this sample standard deviation as
23:08
an estimate of the population standard deviation. So, in place of 𝞂... we we do not know
23:14
the sigma, but we will substitute the value that you have actually measured, which is 40. So, we get the the sigma of the x̿ as 40
23:30
divided by 6 which is 6.67. So, we have to now find out: 𝞵 lies within
23:48
what range of the standard deviation? So, we need to find out.
23:55
So this is the... Let me write it this way.
24:00
P: probability of 𝞵 lies within 12 of x̿. Okay?
24:16
Now notice, here is a value in the whole range. Here is a value 𝞵 and here is a value x̿.
24:30
We are trying to find out... We have found x̿, we are trying to find out how far can 𝞵 be from x̿. Now, this is the same as how far can x̿ be
24:40
from mu. Therefore, we can also write this as probability
24:47
that that x̿ lies within 12 of sorry of 𝞵 right.
25:07
Now, this is equal to probability that x̿ lies within, how many standard divisions,
25:19
it will be 12 by this 6.67 of 𝞵 and this number is the z value.
25:32
In this case it comes to be approximately 1.8. Again if you refer to the z table and read out from this 1.8 number, then the area to
25:46
the left of that. So, 1.8 standard deviation will be somewhere here. Okay? So, we want to find this area and this, this side and the other side.
25:59
So, we want to find this area, this total area actually. So, this is, this is in the positive side, this is the negative side.
26:11
This area we need to find out. But we have actually found from here if we find read out from the z table, then the area to the left... I will get some
26:29
space... of z equal to 1.8 is equal to how much is it; 0.9641.
26:37
Again have to refer to this z table and you have to read this out.
26:48
So, now notice: here we have read to the left of it.
26:53
There are two ways of calculating this whole thing. One is 1 minus this thing, you will get this area, times 2 is one possibility.
27:03
The other possibility is that we have got this area. If you subtract 0.5 is this whole area then you get only this area.
27:14
Then you just get the twice of that. Then it will be within this.
27:21
Okay? So, we need to find... we need to find out how much area is contained, excluding these two tails,
27:30
okay within this area. That can be found this way. So, I will do it the second way. So, 0.9 sorry 0.9641 minus 0.5,
27:43
so, this whole area minus this half area is this area.
27:52
This now I have to twice: this into 2, this comes out to be 0.9282.
28:02
So, the probability that the 𝞵, the actual mean, will lie within 12 of x̿ is this 92
28:17
percent 93 percent approximately. So, this way, even without calculating, without
28:26
actually obtaining infinite number of readings, by taking a finite number of readings, we can infer something of interest regarding the character of the population mean.
28:36
And that ,this this method, actually we will carry through in much of the measurement process
28:44
that we will come across. I will come to that later.
28:49
So you see, we have obtained answers to two questions that we asked right in the beginning
28:54
of the course. The the question was, how many readings do
29:00
we need to take in order to make a confident estimate of the mean? The answer is 25. Now, who gives this 25 number?
29:11
It is actually empirically obtained. We have tried it out and found that, that number works in the sense that, by increasing beyond that number we do not gain much.
29:21
We have ultimately obtained a value which is... which, if repeated many times, will
29:29
give a distribution of the means which is a normal distribution. And from that normal distribution we can extract all the information.
29:37
And the most important information we extract is the standard error of the mean, which I
29:44
just said. I will just call it ‘SE’. Standard error of the mean is is the standard deviation, sorry, the standard
30:06
deviation of of the readings obtained divided by square root of the number of samples.
30:33
In case of a physics experiment, the number of samples means how many times you have conducted the experiments and how many data points you have got.
30:40
So, this is a very important quantifier that we will use many times in the next few lectures.
30:48
Just keep this in mind. This is the standard error of the mean. Okay? With that we will close today and we will
30:57
continue with that in the next class.
Module 6 Lecture 33: - Error Bars and Confidence Interval - Part 01
Transcript
0:17
In the last class we saw that, whenever we make a measurement, we always take a sample
0:28
of some quantity and then we obtain the mean of that sample we get the sample mean and
0:37
the sample standard deviation. And from there we are trying to estimate the
0:43
character of the population mean and the population standard deviation. So, we have a smaller number data and we are somehow trying to assess the character of
0:54
the of the quantity ‘out there’. And in doing so, we have seen that we had
1:02
reversed the argument. For example, if we have the measured quantity
1:10
of x, sorry, x̿ which is the average from the sample, and the the standard deviation
1:22
obtained from the sample. So, these are measured.
1:33
And we are trying to find out. So, we are trying to find out the population
1:42
mean and the population standard deviation. So, this is the target.
1:53
And then the central limit theorem stated that, if the number of data points is sufficiently
2:04
large, then the means will be distributed as a normal distribution something like this.
2:17
And the mean of that normal distribution will be the population mean 𝞵, and the standard
2:25
deviation will be the population standard deviation divided by this square root of the
2:33
number of data points taken. So, that is the claim of the central limit
2:42
theorem. Now, what we had done in the last class in
2:50
an example that we worked out? In that, we were given these and we were trying
2:58
to figure out if we have the a particular value, suppose this is the x scale and here
3:04
is my x̿, we are trying to figure out if they if I if I can define a range around x̿
3:14
and can claim that the actual 𝞵 will lie somewhere in this range.
3:20
And in doing so we argued that, if say, 𝞵 is here, 𝞵 is here suppose,
3:29
then the distance from x to the 𝞵 is the same as the distance from the 𝞵 to the
3:37
x. And therefore, the probability that 𝞵 lies
3:46
within — now here we had written it in the form of a multiplier times the standard deviation
3:58
— within z of z is the multiplier of x̿ and then we said that this is the same as
4:14
P is equal to x̿ lies within the z of 𝞵, sorry.
4:34
And this z is a a a a a factor a factor times the factor is z.
4:52
So, that is the factor and this is the multiplier of the standard deviation so standard deviation.
5:01
Now, if we express it this way then it is possible to obtain it because the value of
5:12
z for each value of z each value of z for example, if the z is here the the area under
5:19
the curve to the left of z can be found from the z table and from there we can solve the
5:27
problem. So, this z value is a factor. There is a multiplier of the standard deviation, something times the standard deviation.
5:36
So, x̿ then x̿ say x̿ is lying x̿ is lying z of 𝞵.
5:49
So, if if if if x̿ is at a distance z from 𝞵 then it is possible to find out what
5:56
is the area under the curve to the left of that value of z.
6:02
And from that, we were able to to calculate the probabilities, and hence the confidence
6:11
with which we can state that 𝞵 will lie within a certain range of x̿.
6:19
You will notice one thing: what is the the standard deviation here?
6:26
It is the standard deviation of the distribution of the means, which is this.
6:33
And in that, we do not know 𝞂 because that is a target.
6:39
That is something that we do not know. That is of the population out there. So, we argued that in the absence of the value of 𝞂, we estimate it by the measured value
6:51
of the standard deviation, which is s. So, we argued that, we will use s as an estimator
7:08
of 𝞂. You might ask how logical will that be?
7:15
Won’t that incur errors in the calculation, in the measurement?
7:21
Yes it will. But there is a logic behind this substitution.
7:27
The logic is that, if the number of samples is reasonably large, then we have seen that
7:38
the the central limit theorem claims that the distribution of the means will be almost
7:47
a normal distribution. And if you increase the number of samples
7:53
even more, it the it it it will not improve the approximation any further.
8:01
So, we know that around 25 is a good number of readings to take.
8:08
Now, if we take that minimum number of readings, then the the theory in statistics—which
8:19
will not go get into the details of that I will not get into—shows that if the number
8:28
of samples is reasonably large, then the difference between s and 𝞂 will be really small.
8:41
And since the actual value is 𝞂 divided by square root of n, and n will be a reasonably
8:49
large number, square root of that, therefore the difference of 𝞂 by square root of n
8:55
and s by square root of n will not be significant. That is why this justifies this use of the
9:07
s as an estimator of 𝞂. But, one thing is clear: that we cannot do
9:13
anything otherwise. We do not have a handle on 𝞂. We only have s and therefore, we have to s use s as a estimator of 𝞂.
9:23
So, we have we will then substitute in place of 𝞂 by
9:30
s which is known, n known and therefore, we have a a a handle on the standard deviation of this curve.
9:41
If we know that, then what factor needs to be multiplied with the standard deviation
9:46
to get the value, that is also known. And therefore, we can then refer to the z
9:52
table to extract the value of the probability. Now, we know we have seen earlier that that
10:06
if now I will plot that as a number here and here is my I give a range.
10:23
This is the value that I have I have measured, which is x̿, and suppose here is x̿ minus
10:33
the standard error of the mean and this is x̿ plus the standard error of the mean.
10:44
Then I know that in the curve that we had already drawn, here I have this normal curve,
10:55
and we are talking about a range which is... this is my x̿ and this is the this value
11:06
is here and this value is here. So, it is basically within one standard deviation,
11:14
and we know that the the area under this curve here is 68.3 percent of the whole.
11:30
What does that imply? It implies that if I define a range which
11:38
is x̿ minus the standard error (standard error means the standard deviation divide
11:45
by square root n) and x̿ plus the standard error... If this range is defined, then I can be certain that the actual mean will lie within this
11:58
range, and I can state that with a confidence of 68.3 percent. So, this is important. This is important to understand what is the
12:09
actual meaning of the statement. And this, in many cases, is written as the
12:17
error bar. So, you we will see graphs something like
12:23
this. So, these are the data points.
12:43
And if you add the error bars these will look like... you normally put the extremities like
13:11
this. So, this is how the graphs are actually drawn.
13:22
This means here is suppose a parameter or an independent variable, I would rather rather
13:37
say variable, and here is a dependent variable. Now, for each independent variable, you measure
13:58
the dependent variable and you may get these values. Okay? But you will also specify by an error bar.
14:06
And what does that error bar signify? It signifies that you are 68.3 percent confident
14:16
that the actual value the actual value of the dependent variable for that independent
14:22
variable will lie within this range. So, with 68 percent confidence you will state
14:29
that. That is the meaning of the error bar.
14:35
Now, you might say that the 68.3 percent is not a very large extent of confidence.
14:45
Yes, surely, we will have to deal with that. We would see how to to represent a higher
14:53
level of confidence. But in general, the the meaning of the error
14:59
bar is that. So, whenever you will read an error bar, you see an error bar in a paper, you have to interpret that accordingly.
15:07
It does not mean that the actual value will be in this range. The actual value can be as well be outside, because this this confidence level is not
15:16
very large. That means, essentially you are stating that there is 68 percent probability that the the actual value the actual value that we are
15:27
trying to measure, which is out there, will lie somewhere in this range. Okay?
15:35
Sometimes we state the the value, for example, suppose we have measured something and we
15:41
have we have got x equal to, say, 3.56 centimeters. But, then we will have to state it with an
15:52
error which is plus minus, say, 0.03 centimeters. So, we always state it like that, because
16:02
we can never state the value exactly. Because we know that it is subject to some
16:08
random errors. Okay? Sometimes these are also expressed a little bit differently, as a percentage error.
16:19
So, that can also be expressed as a percentage error, something like this: I will write x
16:29
as the average value that we have measured. This is in centimeters may be.
16:37
And then plus minus, now you have to put the standard error, which is say standard error
16:45
I I can write that it δx, the change in x divided by your x̿, which
16:53
is the extent of error in fraction into a 100 these many percentage.
17:01
This is the percentage error calculation. Okay? So, you might state the result in both these ways.
17:09
This is in absolute value and this is as a percentage error.
17:14
So, the point that I am making is that, whenever you make an observation in measurement, you
17:20
state the result of the measurement always this way, and the extent of this error that
17:27
you state is also objectively calculated. Let me
17:34
let me just illustrate that by means of an example and then I hope that will be clearer.
17:42
Suppose suppose you have made a measurement of two
17:50
variables x and y, and you have made a large number of data points, say n equal to 25.
18:00
25 data points you have calculated and then from there you have you have found by calculating
18:08
that x̿ is 5.018 and Ȳ is 3.335. Okay?
18:25
But, the data that you have calculated: this 25 data points for x, 25 data points for y,
18:34
from there you can also calculate the s of the x variable; s is the standard deviation
18:43
of the x variable. And suppose you know how to do that. you have... I have already said how to do that.
18:48
You have found that that to be 0.16. And the s of y is, say, 0.21.
19:00
Then then how do I specify these values? We need to calculate the standard error.
19:13
So, standard error in x will be 𝞂 by square root of n.
19:25
Now, 𝞂 we do not know, but we know the s. Therefore, we substitute by that. So, 0.160 divided by square root of n, is
19:37
5, is equal to 0.032. And the standard error in y is this 𝞂.
19:49
This would be x and this would be y y root over n.
19:57
And we again substitute that by this standard deviation in y. Major standard deviation in y. So, 0.211 by, again, 5 because the number
20:10
of data points were the same. And then this comes to be 0.042.
20:17
And therefore, having done this calculation, we will state that I have measured x as here
20:27
5.018 plus minus this 0.032 and I have measured y as this 3.335 plus minus 0.042.
20:53
Notice one thing, that after having these values that you have actually measured, when
21:01
you when you calculate the the mean, you could have calculated up to a larger number of decimal
21:08
points. Similarly, for the standard deviation you could have calculated to a large number of decimal points.
21:14
If you have a calculator with 8 digits, you can do that. But it will make no sense because the measurement has been taken with some kind of apparatus
21:24
which has a least count and it makes no sense to specify something to a least count that
21:31
is below that least count. So, if the measuring apparatus has an accuracy
21:38
which is meaningful to the third decimal place, you should specify everything only up to third
21:44
decimal place. There is no point going beyond that. That is why, in this case I have expressed everything up to the third decimal place.
21:54
But remember to what decimal place you will specify it. There is no pre-assigned prescription for that.
22:02
You have to do that depending on the instrument that you use. Depending on the accuracy of that instrument. Okay?
22:12
Notice that everything hinges on the idea that in the distribution of the means, the
22:20
say, standard error of the mean or the standard deviation of this graph is 𝞂 by square
22:27
root of n. And I have already told you that in the in
22:33
the normal distribution curve you can easily integrate the normal distribution curve and
22:39
find out how much area is contained within some specifically ranges... specific limits.
22:45
And if it is up to the standard division of this graph, then it is 68 the the area under
22:53
the curve. So, area within 𝞵 plus standard sorry 𝞵
23:09
minus to 𝞵 plus standard error, 𝞵 plus standard error, this range, is 68.3 percent.
23:31
And we have also seen that the area if if you can calculate this, then you can also
23:36
calculate how much does it have to be taken so that the area under the curve curve is
23:44
95 percent, and that has been calculated. Area within I want to have this at 95 percent
23:58
𝞵 minus it is 1.96 1.96 standard error and 𝞵 plus 1.96 standard error.
24:13
This range is actually 95 percent. And the area within sorry 𝞵 minus if you
24:35
want to have 99 percent then 2.58 SE and 𝞵 plus 2.58 standard error.
24:54
So, if you consider a larger range, which is 1.96 standard error, this is a standard
25:11
error, then the area that is contained this area
25:17
that is contained which is this area I will I will patch it this area is 95 percent.
25:29
This has great important... In some fields the the confidence level of
25:40
68.3 percent is considered too low and there the demand is that you have to state it with
25:50
a confidence level of 95 percent. And if that is so, your error bar error bar
25:58
will have: this is the mean value that you have calculated and this is x̿ plus 1.96
26:15
standard error and this is x̿ minus 1.96 standard error.
26:24
In that case you have to specify that way and this is actually true for most fields.
26:32
So, but there are some fields that demand even more level of confidence when you state
26:42
the result, for example, 99 percent. In that case you have to put 2.58 here.
26:52
And there are some fields, especially something like for example,
26:58
the discovery of a new particle in particle physics, the discovery of gravitational wave,
27:06
is a discovery... in case of the discoveries the demand is far larger.
27:14
The demand is something that is stated as 5 𝞂.
27:19
What does 5𝞂 mean? So, in in in discoveries, when we will say something has been discovered, in discoveries the demand is 5𝞂.
27:38
What is the 5𝞂? It is this number. This number will then become 5. That means, almost the whole area is enclosed
27:50
within 5𝞂, 5 times the standard error of the mean and practically the whole area is
28:01
enclosed. What does this physically mean? It physically means, I will just write it; it physically means that 5𝞂 will mean I
28:10
will put the line here yeah this means that only one in 3.5 million data points
28:46
can lie outside this range. Which means that if the result that is been
29:02
obtained, for example, the discovery of Higgs boson was a an observation an observation
29:11
where there was there was a kink in a graph. Now, if that kink happened due to random chance
29:22
event, then the possibility of such a random event being detected is one in 3.5 million.
29:35
Only when we reach that level of confidence we say that we have made a discovery.
29:42
So, it is very very exacting demand for the scientific community.
29:47
They have to make measurements and repeat it a large number of times and then only one
29:53
can reach that kind of 5𝞂 level of confidence. That means, if the observation that has been
30:02
observed is caused by ah something that is not what is intended to be,
30:08
then the probability of that happening is only one in 3.5 million. That means, the area under the curve within 5𝞂 is absolutely there
30:20
the amount that is remaining is only this much.
30:26
So, that is a kind of demand in case of discoveries.
Module 6 Lecture 34: - Error Bars and Confidence Interval - Part 02
Transcript
0:17
But whenever you make any statement of a measurement, you have to put the error bar and depending
0:24
on the field in which you are reporting. There is some kind of a standard.
0:30
Some fields demand 95 percent confidence, some fields demand 68.3 percent confidence.
0:36
And depending on... you can state your error bar.
0:42
But, a statement of a measurement without an error bar is itself unacceptable.
0:50
Because, it violates the basic principle of measurement that it has to be repeatable.
0:59
If somebody else does this experiment somewhere else, he or she might be getting a different
1:05
value of x̿. But, his value or her value will remain somewhere
1:11
in this range and if that experiment is repeated again and again, it will be found that around
1:18
95 percent of the times the value that you get are remaining within this range.
1:24
Therefore, the other experiments done by other people are actually conforming to the earlier
1:31
measurement. So, the measurement is repeatable in that
1:37
sense. Notice a couple of things.
1:41
Suppose I have, suppose I have made ah something like this
1:48
measurement. And now, the the reviewer says that this error
1:55
bar is too large. See again the meaning of the error bar is
1:59
that I am 95 percent confident in this case, I am 95 percent confident that the the actual
2:05
value out there will lie within this range. But if this range is too large, then the the
2:12
reviewer or the editor of the journal may think that it is too vague.
2:16
It has to be more, you know, accurately measured, which means that they might demand that it
2:21
has to be half, it has to made half, a shorter range.
2:26
How do you do that? Simple.
2:29
Because this range depends on the standard error and the standard error depends on the
2:35
number of measurement samples, and that n, square root of n.
2:41
Therefore, if the the error bar has to be halved, the number of samples has to be 4
2:49
times. So, if you take 4 times the number of samples,
2:52
then you can halve the error bar. Okay?
2:58
This point number one. Point number 2 is that, you are after all
3:02
taking samples from a population out there. If there is some kind of a bird whom you are
3:08
sampling and you are trying to find out its average body weight,
3:11
then there is a population out there, but the size of the error bar will not depend
3:19
on the size of the population. So, long as this the population size is much
3:25
larger than the sample size. We have done a sampling and the population
3:30
size is much larger. There is 1 million birds out there, I have
3:34
caught some 15 and I have measured it. Then, it will not depend on the population
3:39
size. The demand is that the population has to be
3:43
much larger than the sample size. But, as I have said, it will depend on the
3:50
sample size. So, if you want to make the the error bar
3:54
smaller, you have to take a larger number of samples.
3:58
There may be some cases where you might not be able to take 25 samples.
4:08
And what to do that in that situation? I will come to that later.
4:16
For example, in the in the problem that I just just calculated,
4:21
suppose I have calculated the x̿ and we had calculated x̿ is equal to 5.018 and we had
4:35
calculated SE of x as 0.032. Then what should be with the error bar for
4:47
a 99 percent confidence? It will be, it will be the range 5.018 minus
5:01
if it is 99 percent confidence then it is 2.58 2.58 times the standard error 0.032.
5:14
Ah 2, 5.018 plus 2.58 times 0.032 and this can be if you if you calculate that it comes
5:32
out to be 4.937 to 5.102. So, with a confidence level of 99 percent
5:48
you can state that the actual value will lie in a range something like this.
5:54
So, this is a very concrete statement. Having made the measurement you are making
5:59
a very concrete statement that I am 99 percent confident that this is the range in which
6:05
it will lie. So, this is what comes out of a measurement.
6:08
This is the scientific way of making and stating a measurement.
6:14
There are many situations, where you might not be able to to collect 25 or more samples.
6:26
Situations like that occur, for example in field buffer field biologists or geologists,
6:33
where getting each data point involves going to the field, collecting samples, coming back
6:38
with the samples, measuring them: expensive proposition.
6:43
In other fields like physics also, getting new data points might involve lot of expense
6:49
and setting up new apparatus which might not be always possible.
6:54
I would say that that is not desirable. Wherever possible you should obtain 25 data
7:00
points, because then you are confident about the result.
7:03
But, suppose it is not possible. Then do, what do you do?
7:07
Then, so this is the situation when the data size is small.
7:23
I have already said that in that situation, the central limit theorem will not be exactly
7:31
applicable. Central limit theorem says that if the data
7:35
size is the sample size is 25 or more, then the sample means the distribution of
7:45
the sample means would approximate a normal distribution.
7:48
If the data size is small it will not approximate a normal distribution.
7:52
But, it will approximate some distribution. And what distribution it approximates will
7:59
depend on the data size. On that basis, we can still extract some meaningful
8:07
results, even if the data size is small. But remember, this is not a shortcut.
8:15
This is something wherever possible, you should actually take
8:20
more than 25 data points and do it the way I earlier said.
8:23
But in the cases where you cannot do that, there there is still a way.
8:29
The way is that, in that case it will not go into a normal distribution.
8:35
But it will be some distribution. That some distribution will be... is called
8:40
a t distribution. And that distribution has been measured and
8:49
we now have the t tables from which similar results can be obtained.
8:54
Let me illustrate. First, when we when we were actually doing
8:57
the z measurement z, what was the definition of z?
9:02
It was basically the the average value that you have measured minus the the population
9:13
mean divided by the 𝞂 of that x. Which is nothing but x measured minus 𝞵,
9:25
the mean value of x measured, minus 𝞵 by 𝞂 by square root of n.
9:33
Now, if the n is small, then we do not call it a z value, and do not refer to the z table
9:42
because then it will be erroneous. But we call it the t,
9:47
the measured value of t. But the t, its definition is still the same.
9:52
The measured mean minus the the population mean divided by the 𝞂 by square root of
10:05
n. Again in this case, we do substitute 𝞂
10:13
by the measured s, the the standard deviation. But we understand that that will incur some
10:20
error. We understand that, but there is no other
10:23
way. So, we do use this this logic still.
10:28
In order to continue, in order to extract some kind of a meaningful result.
10:33
Let me illustrate this with an example. Suppose, you could take only 9 measurements
11:12
on the mass of a particle. Let me write the measured values.
11:28
And
11:46
the measured values are 16.2,—whatever unit— 19.7, 21.8, 15.6, 19.0, 18.7, 16.9, 21.7 and
12:14
20.2. So that, this gives...
12:23
from this you can easily obtain x̿ is... x̿ is 18.87, sorry let me write x̿, x̿
12:41
is 18.87 and the s is 2.2583. Now the question is, on the basis of this
13:01
result that you have got, on the base of this result that you have got
13:06
can you state that the actual mass of the particle is... see the the average that is
13:14
calculated with this, the the mass of the particle is below 21?
13:20
So, can you state, state or rather I will write
13:39
is there sufficient evidence that mass of the particle is less than 21?
13:53
Now, what do you mean by sufficient evidence? It is basically that the probability that
13:59
the statement is wrong is less than 1 percent. Sufficient evidence means, probability of
14:09
‘wrong’ is less than 1 percent. So, how do we proceed?
14:18
We have already calculated the x̿ and s. Now, the situation is is the same as ‘what
14:31
is the probability of getting this value of x̿ if the the mass was actually 21?’
14:44
Okay? So, there is a range.
14:48
It can be above 21 also. But, if it is 21 21 or above.
14:52
So, we are we are stating that ‘it is not 21 or above’ therefore,
14:57
its lowest value is 21. So if the value is 21 then, what is the probability
15:02
that I am getting, what I am getting, 18.87?
15:05
What is the probability of getting that? So, our approach will be to assume that 𝞵
15:15
assume that 𝞵 is 21, and check for the probability P that x̿ is
15:29
equal to 18.87. That is we are trying to figure out.
15:39
Okay? Now, if this probability turns out to be less
15:44
than 1 percent, then I can make that statement. If that probably turns out to be more than
15:51
1 percent, then I do not have sufficient evidence. Okay?
15:55
So, this is how we proceed. Now, in this case we cannot consult the z
16:04
table. We have to consult the t table instead.
16:07
First let us calculate the t value first. t is, again, x̿ minus 𝞵: x̿ is 18.87
16:19
minus 21 divided by 𝞂 by square root n. And in this case, here I have square root
16:32
of 9. But 𝞂, I do not know.
16:34
And therefore I have to substitute by the measured value here.
16:37
So, this is... So, this is 18.87 minus 21 by,
16:47
I will substitute by the measured value. Again it will incur a bit of error, but this
16:53
is all we can do really. Square root of 9 is 3.
16:59
This is equal to -2.83. Alright. Now, with that in hand, we have to consult
17:10
the t table. Let us consult the t table now.
17:15
So, here is the t table. Notice here, this is organized in a way that
17:22
is different from the way the z table is organized. You notice that there is something called
17:27
‘significance level’. The significance level is 1 minus the confidence
17:31
level. So, for 99 percent confidence level the significance
17:35
level is 1 percent; for 95 percent confidence level the significance level 5 percent; and
17:41
so on and so forth. So, in this case, the demand was to have 1
17:44
percent significant level. And so we have to look at this column.
17:49
Now, here is the degrees of freedom. Degrees of freedom, as we know, is 1 is is...
17:56
the number of data points minus 1. Number of data points was 9 and minus 1 is
18:02
8. So, we have to go along this row and this
18:06
column and we get this value. So, this is 3.355.
18:22
That means, that we had we had the normal distribution.
18:30
It will not be normal distribution curve; it will be a different curve.
18:33
But nevertheless, the 1 percent area will be available outside 3.355.
18:51
And since it is symmetric, So, it, 1 percent area will be available out
18:56
of outside minus 3.355 also. So, 1 percent area is to to the to the outside.
19:08
Okay? So, our value that we got was minus 2.83 t
19:16
value. So, minus 2.83 is somewhere here, which is
19:26
to the right of this. Therefore the area to the to the outside of
19:34
this will definitely be bigger than 1 percent. And therefore, for this particular problem,
19:43
for this particular problem, we cannot have sufficient evidence to state
19:49
that the mass of the particle is smaller than 21.
19:54
Why? Again let me repeat.
19:57
Why? Because, we our demand was that the the probability
20:03
that this statement is wrong should be less than 1 percent.
20:07
We assumed the limiting value 21, and we calculated what are the odds of getting this value of
20:15
x̿ in an experiment and we found that the odds, the the probability, will be more than
20:23
1 percent. And therefore, therefore the the probability
20:31
that I am wrong in making this statement is more than 1 percent.
20:36
And therefore, we do not have sufficient evidence to make that claim.
20:41
So the probability, probability of getting a t value less than -3.355 is is 1 percent.
21:09
That is what the table says, and and then, because of this, if the mean is 21...
21:24
If the mean is 21, the probability of getting getting x̿ as 18.87 is more than
21:47
Therefore, we cannot state from the data that the the mass of the particle is less than
22:04
21. That is the conclusion from this experiment.
22:08
Okay? So, I will stop here and we will continue
22:11
later.
Module 6 Lecture 35: - Measurement of a Proportion - Part 01
Transcript
0:08
So, we have learnt how to obtain measurements of a value, a value which can take any number
0:28
and that comes from some kind of a measurement, some kind of a reading of an instrument.
0:33
And we have learnt how to obtain the reliable mean value of it, how to state it to an external
0:41
audience in the form of ah error bar. But there is another kind of measurement that
0:48
a scientist often has to do. It is a measurement of a proportion.
0:53
So, the measurement of a proportion, of a proportion.
1:07
Just consider the experiment that Mendel did. Gregor Mendel, he crossed two varieties of
1:21
pea plants: one tall, another short. And it was found that there is nothing in
1:28
between, so, tall or short. And he crossed these two varieties and in
1:34
the next generation he found that all the offspring are tall.
1:39
And then they crossed within that generation and he found that a part a proportion of that
1:45
is tall and another proportion of that is short.
1:49
So, his task then was to find out what proportion is tall.
1:57
So such kind of measurements are the measurements of a proportion.
2:02
There are various situations where one can have this kind of proportion measurement problem.
2:12
For example, in any evolutionary process one encounters this kind of situation.
2:20
For example, a very well documented process of evolution that happened before human eyes
2:27
was a species of moth in England. The moth was originally whitish in color and
2:36
they sat on the bark of the trees which were also whitish in color.
2:41
So, they could properly camouflage, the birds could not find the moth and eat them.
2:48
And for millennia that was the stable situation. But with the advent of modern civilization,
2:54
with the advent of atmospheric pollution, the bark started turning more and more darker.
3:03
As a result, the the insects the moths became visible and they could be eaten by birds and
3:11
at that point it was found that over a very short period of time,
3:17
the whole species changed into a brown darker species, brown species, which could be again
3:23
adapted to that particular colour of the bark. Now, when that happened essentially what happened
3:30
was, there was a mutation within the species which
3:33
produced a coloured offspring and that coloured variety was chosen by nature.
3:39
It was natural selection, which was selected by nature.
3:43
And so in successive generations, the coloured ones, the brown variety of the moth, their
3:50
proportion increased. And finally, after some time there was no
3:54
white ones left. So, that was a speciation event, happening
3:59
before our eyes. But if a scientist is studying that speciation
4:04
event, then he will have to count or find out the proportion of the brown moths in each
4:11
generation and that will tell you how is speciation actually happens.
4:16
So, it is a problem of measurement of a proportion. Similarly in every field there are similar
4:25
types of proportion measurement problem. If a beaker has two different types of microorganisms
4:31
and you are trying to find out which one or suppose one is a phyto plankton, the other
4:39
is a zoo plankton. One is in a vegetative kind, plant kind, the
4:45
other is a animal kind that eats on the plants. And as time progresses, the proportion of
4:52
the two will change and that leads to the dynamics and one has to study that by studying
4:57
the proportions. So, there are various situations where one
5:02
has to measure proportions. So, let us
5:08
let us attack that problem because that problem is slightly different from the measurement
5:12
problem that we have encountered so far. So, we assume that there is some entity whose
5:20
property we are measuring. But that can take only two values: either
5:25
a tall pea plant or a short pea plant, nothing in between tall or short.
5:31
If we are trying to find out the the proportion of the talls in the whole population, then
5:38
we will, if we find a tall one we will say 1 or if
5:41
we find a short plant we will say 0. So, there are two possibilities 1 or 0.
5:47
Similarly, in the moth population, if there are two possible varieties: the white ones
5:52
and the brown ones, then may be the brown ones will be called 1 and the white ones as
5:57
0. The the point that I am making is that, in
6:00
a that kind of a proportion finding problem one has the the entity given as either 1 or
6:09
0, that kind of a situation. So, you will let us...
6:14
Let us consider the situation of the moths, because it is better to work with an example
6:19
to make things clearer. So, we are counting moths and finally, trying
6:25
to find out what is the proportion of the brown moths in the whole population.
6:30
There are brown moths as well as white moths. What is a proportion of the brown moths?
6:34
When we catch one and we see that it is brown or white, we assign a number 1 or 0 to it.
6:45
And so let us call that measurement to be Y.
6:51
So, Y; so, let us call it Y. Y is the is the result of one measurement.
7:13
Now, that can be either 1 or 0. When would it be 1?
7:28
When if the moth is brown. And 0 if the moth is white.
7:43
There are two possibilities 1 or 0. So, the Y can get two values, two possible
7:51
values, 1 or 0. Now we ask and suppose in the population we
7:59
assume that say the in the population... We assume, in the population
8:15
the proportion of brown moths is, say, 60 percent, and white moths 40 percent.
8:39
Suppose this is, we are working with an example in in mind.
8:43
So let us assume these values. In that case, in general you will have the
8:53
there there will be a probability of finding 1 and another probability of finding 0.
9:01
So, p for 1 and 1 minus p for 0. In that situation, what will be the mean value
9:18
of Y? I have collected many and then I have to,
9:23
I have to divide by the total number of samples and thereby we obtain the mean value,
9:29
the mean value will be the 𝞵: the mean value of Y will be...
9:37
We will do it by weighing the various possibilities. So, the one possible value is 1, weighted
9:52
by its probability, plus another value is 0 weighted by its probability.
10:03
That yields p. Therefore the mean of Y should be p.
10:08
In this case it would be 0.6. You would notice that 0.6 is not the value
10:15
that Y can take. It can either take 1 or 0.
10:19
But the mean value can be a fractional number. Now, what will be the variance of this?
10:32
Let us try to work out the variance. The variance can be obtained as a weighted...
10:48
Well, what is variance? The difference between the, the value that
10:53
I get and the mean, squared, and its average. So, there are two possible values.
11:03
So we will simply do a weighted sum. So, weighted sum of the squares of the distance from the
11:10
mean. Now, there are two possible values 1 or 0.
11:15
If it is... Let me write 𝞂y, it’s variance.
11:21
Therefore square is one possible value is value is 1 minus the mean value,
11:32
this is the difference from the mean, squared, and I have to weigh it by its probability.
11:42
So, into 0.6 plus the other possible value is 0.
11:51
So, 0 minus 0.6, square, into its probability 0.4.
11:59
So, you see, the total variance turns out to be, it will be 0.24.
12:10
So, notice the the the logic: that there are only two possible values 1 and 0.
12:19
If it is 1 then the distance from the mean is this much, its square, that has to be weighted
12:25
by the probability of getting 1. Similarly another possible value is 0, distance
12:30
from it is this one, its square and you have to weight it by the probability of getting
12:35
0. And there thereby you get the variance.
12:38
So, let us do it in general, in terms of p. So, in general,
12:45
let us do it here, in general, our 𝞂y² will be this was p.
13:09
So, p times 1 minus p square plus this was 1 minus p 1 minus p times p square.
13:26
Okay? this is basically in terms of p is this.
13:31
So, let us just work it out: p 1 plus p square minus twice p plus 1 minus p, p square is
13:48
equal to p plus p cube minus twice p square plus p square minus p cube and p cube cancels
14:04
off and we are left with p minus p square, p into...
14:15
Okay. So, that then is the variance of the observation
14:23
individual observation. The variance is this and we get then the standard
14:28
deviation 𝞂y is the square root of that [√(p(1-p))] square root of p into 1 minus
14:38
p. So, this is the result we get for a single
14:43
observation. That means, I make an observation, I get a
14:46
value. I make another another observation, I get
14:49
another value. If we go on doing that for a long time, then
14:52
it will get a distribution and that distribution we will have a mean p and the standard deviation
15:00
this, and this distribution is called the Bernoulli distribution.
15:09
But you would notice that we actually do not make the measurement that way.
15:14
How do we make the measurement? The way we actually make the measurement is
15:19
that, from the population we collect a number of moths and then from that number of moths,
15:26
say n, we find out how many are brown and how many are white.
15:36
So, so in general we we do it a slightly different way.
15:41
We get a sample right. So, we get a sample.
15:46
So, we we... let me draw a line here because now it will be a slightly different procedure.
15:54
We take a sample, say, of 10 individuals. We take a sample of 10 individuals.
16:13
Now, from that we will find out how many are the tall ones how many are the brown ones.
16:20
So, how many are 1s and how manys are 0s. And, for each combination, each number,
16:30
there will be a probability then. Can we find that probability?
16:33
Let us try to work it out. So, the point is that, we have assumed that
16:39
the p, the probability of finding 1 in the population, is 0.6, and probability of finding
16:44
0 in the population is 0.4. On that basis we are proceeding.
16:48
So, we are now taking 10 samples. And now we are asking what is the probability
16:54
of well on an average 60 percent will be brown, on
17:01
an average 40 percent will be white. And we have drawn 10 samples.
17:07
And therefore, we expect that, 6 would be brown and 4 will be white.
17:11
Will that really happen? No, not really,
17:15
not really because because of the of the, you know, we are ultimately doing a sampling
17:21
out of a completely randomly mixed population. And therefore, there is no reason to to have
17:26
to to expect that for every sample that we draw,
17:30
it will reflect the population mean. That will not happen.
17:33
But still we can calculate, what is the probability of probability of of 6 1's out of 10 samples?
17:48
How we can do that? Suppose we take a particular sequence.
17:56
Suppose we have we have we collected 10 and when we find out the first one then it comes
18:03
to be white so 0, second one is also white, third one is brown,
18:10
1, and therefore, fourth one is brown brown again, white, brown.
18:20
How many 4. Suppose we have got it in this sequence, what
18:28
is the probability of this sequence? That is rather easy to calculate, because
18:40
what is the probability of getting 0? 0.4.
18:43
What is the probability of getting 1? 0.6.
18:47
Therefore the probability will be when I have already got the first one, it had a probability
18:55
of 0.4. When I got the second one what is a probability?
19:00
That second one will also be 0, that means, white, it is 0.4.
19:05
time 0.4. So, effectively by the law of multiplication
19:09
of probabilities the probability can be easily calculated as 0.4 first one times second one
19:17
0.4 because it is 0. Times the next three are ones.
19:23
So, 0.6 times 0.6 times 0.6 times this one is 0 so, times 0.4 times this was 0.6
19:39
4 6 6 so, 0.4 times 0.6 times 0.6 and this is it is easily seen that it does not really
19:54
matter in which order the 0s and 1s appeared. What really matters is how many times they
19:59
appeared and so we can write this as 0.6 appeared 6 times and 0.4 appeared 4 times.
20:13
So, it is 0.0012. So, this is how these are calculated.
20:22
But you will notice that I had initially set out the problem: 6 1s out of 10 sampler.
20:28
This is not the only way you can have 6 1s out of 10 samples.
20:33
It is possible that the first 6 are 1s and then the last 4 are 0s.
20:37
That is also another possibility. So, there are various possibilities.
20:44
But notice that all these possibilities will have the same probability.
20:50
So, all these possibilities for different possible ways of getting 6 1s and out of 10
20:56
samples, all of them will have the same probability. So, all we need to do is to find out how many
21:01
ways we can have that 6 1s and multiply that by this number.
21:10
And we know that the number of ways by which you can get 6 1s out of 10 samples is simply
21:17
10 choose 6. So, the probability of 6 1s out of 10 will
21:35
then be 10 choose 6, this is how it is written 10 6 and that has to be multiplied by this,
21:45
into 0.6 to the power 6 times 0.4 to the power 4.
21:58
And this is, we know how to write that: it is 10 factorial divided by 6 factorial times
22:10
10 minus 6 factorial times this number, which you have calculated as 0.0012, and this
22:24
comes out to be 0.2508. So, the lesson is that, even though
22:35
in the population the number of the proportion of the brown moths is 0.6, if I draw a sample
22:45
of 10, the probability that I will find 6 of them to be brown is only 25 percent
22:52
is rather small; rather small number. And we can similarly find out what is the
23:00
probability of having say 7 1s and 3 0s.
23:09
So, similarly probability of 7 1s and 3 0s will be it is not difficult to calculate that
23:25
will be 10 choose 7, 7 1s into 0.6 to the power 7 into 0.43.
23:51
And that way we can calculate what is the probability of getting only 1 out of 10 10
23:58
samples, only 2 out of 10 samples,
24:00
and so on so forth, and we can plot a graph, and we can plot a
24:06
graph. And the graph here: it is well it is possible
24:19
to get 0 1 2 3 4 5 6 7 8 9 10. 10 samples we have drawn and it is possible
24:39
to get all of them white, it is possible to get all of them brown, it is possible to have
24:44
all the intermediate ones. And you will find that it is the the largest
24:49
was probability probably will have happened at at at 6,
24:54
because the proportion of the moths in the out in the population is around 60 percent
25:00
proportion of brown moths 60 percent. So, this will be smaller, this will be smaller
25:08
and this will be again smaller. So, you will get distribution.
25:16
And if you now increase the number of samples, that n, if you now increase it, you will get
25:23
more possibilities and therefore, each possibility will have a probability assigned to it.
25:31
And as you increase and increase this the number of samples, it will slowly become a
25:44
a smooth distribution. And it will tend to a normal distribution.
25:57
It will tend to a normal distribution and we will...
26:02
The moment we claim that it will tend to a normal distribution, we immediately face the
26:07
question, what will be the mean and what will be the standard deviation?
26:09
We immediately face that question. We will; we will take care of that.
26:14
So, what I have dra... driven at is that, when we take samples from the population and
26:22
find out the proportion within that sample, then the various possibility we will have
26:29
a distribution like this, and as you increase the number of samples that distribution will
26:35
tend to become a normal distribution. Okay?
26:40
Now, this distribution of only the discrete ones is the Bernoulli is the is the binomial
26:47
distribution, and as the number increases it tends to the
26:52
normal distribution. Now, we face the problem of finding out the
26:58
the mean and the standard deviation of that normal distribution.
Module 6 Lecture 36: - Measurement of a Proportion - Part 02
Transcript
0:08
So, we have come to a situation where the problem is that, from the population we draw
0:23
a certain number of samples, say n samples, and a part of that we will be found to have
0:38
the value of 1, a part of that we will have the value of 0.
0:43
And we are trying to find out what proportion has the value of 1.
0:48
So, we have drawn n samples. Suppose the number of 1s in that n sample
0:59
is called X. So, X the number of 1’s in the sample of
1:16
n individuals. So, X is a fraction of n and we will now face
1:31
the problem of finding what is the mean of X, the standard deviation of X, and so on
1:38
and so forth. If I draw that n number of samples again and
1:45
again from that population, I will not get the same value of X every time.
1:51
I will get different values, and that those values of X will also have a distribution.
1:59
And we have just concluded that, if the number of samples becomes large, that distribution
2:05
will become more or less a normal distribution. And now we are we are facing the problem of
2:13
finding what is the mean of X, and what is the standard deviation of X.
2:18
So, our problem is is the mean of X and the standard deviation
2:33
of X. Now, X is the number of 1’s in the population
2:39
in in the in the sample of n individuals. Therefore, in finding out what X is, what
2:47
I am doing is that, I am picking up each individual from the sample and we are asking whether
2:52
it is 1 or 0? Again I am picking the second individual,
2:54
I am asking: 1 or 0? This is the same as what we are doing earlier.
2:58
That means, we are actually making a measurement of the Y’s.
3:01
Each measurement is Y, which can have two values 1 or 0.
3:05
We have seen that earlier. So, X, the measurement of X is actually n
3:12
measurements of Y. So, which is nothing but Y plus Y plus Y that
3:20
goes on n times. So, if that be so, we have already found out
3:31
what is the mean of Y. Then the mean of X is nothing but the mean
3:37
of Y, n times. So, then we can argue that, the the mean of
3:46
X can be simply expressed as the mean of Y plus the mean of Y plus the mean of Y ...
3:56
n times, and we know what the mean of Y is. We know that the mean of Y is p.
4:08
Therefore, n times of p is np. So, that should be the mean of X.
4:18
Now, what will be this variance? I would argue that, we would carry carry out
4:24
the variance exactly in the same way. So, the variance of Y variance of X, so, variance
4:33
of X should be again each measurement of X is nothing but n measurement of Y, and we
4:49
know the variance in the measurement of Y, and therefore, this is nothing but the n times
4:56
the variance of Y. Okay?
5:04
And the variance of Y we have already learned, n variance of Y is p into 1 minus p.
5:13
So, that should be the variance of X. So, we have a distribution whose the variance
5:22
is known. Therefore, the standard deviation standard
5:25
deviation would be square root of np 1 minus p.
5:36
Okay? Now, what are we actually trying to find out?
5:42
We are actually trying to find out the proportion the measured proportion.
5:50
The measured proportion
6:04
the measured proportion is that number that we have found: X is the number that we have
6:11
found, divided by the total number of samples. That is the measured proportion.
6:15
Let us call it measured therefore; it is not the proportion out there.
6:19
Let us call it with a hat. So, that we know that we are talking about
6:24
the measured proportion: the 1’s that we have measured using the number of, n number
6:29
of samples is ̂p̂ and that will be the that will be the measured proportion.
6:38
And if we do a large number of trials of taking n samples each time, we will get a distribution
6:49
of the measured proportions. For 1 1 sampling; that means, we have taken
6:56
n samples, we have got a measured proportion. If we do that again, taking another n samples,
7:01
we will get another value of this. A third time you will get another value of
7:05
this. Ultimately, the p̂ will have a distribution.
7:10
What will be the mean of that distribution? What will be the mean of the distribution
7:15
of the p̂’s? So, that will be let us call it mean of p̂.
7:26
That will be the mean of X mean of X divided by n.
7:36
Since the p is X by n, therefore, it will be this, and mean of X is something we know:
7:41
n times p. So, n times p by n.
7:45
Therefore, it will be p. So, the the... if I repeatedly make measurements,
7:52
each time taking n samples, I will get a distribution and that distribution will have a mean which
7:58
is the the proportion of the proportion ‘out there’ in the in the population.
8:05
So, that is a good thing. That we can obtain the the actual proportion
8:14
by making repeated measurements, every time taking n samples.
8:20
And what will be the standard deviation? The standard deviation, σ of p̂, that will
8:30
be the the σₓ divided by σₓ divided by there are n samples n.
8:41
Now, we know that σₓ was square root of np 1 minus p, and here is n.
8:55
Therefore, this comes to be square root of p 1 minus p by n.
9:07
So, the the conclusion is that if there is a proportion in the population out there and
9:17
I am trying to find it using a sampling process. I am drawing samples, n samples each time.
9:25
If I repeat the process again and again, then every time I will measure a different value
9:31
of the the measured proportion p̂, and that will have a distribution.
9:38
And that distribution will have a mean at the population mean p, and that mean that
9:45
p̂ will have a distribution whose standard deviation will be this, a well defined number.
9:55
Well you might ask: what is the guarantee that this distribution will be a normal distribution?
10:03
Earlier our argument for rooting on a normal distribution was the central limit theorem.
10:15
But here we cannot apply the central limit theorem, because it is a different problem
10:19
we are dealing with. So, how do we ensure that it will be a a normal
10:26
distribution? Now, it has been found that the question is
10:32
is legitimate. It has been found that, well it goes by a
10:39
by a rule of thumb. It is not not difficult to see that, if the
10:44
number of 1’s in the population is too small, it is like a dwindling dwindling population,
10:50
something close to extinction, if that is so, then the distribution will not be a a
10:58
normal distribution. So, there are situations where it will not
11:02
be a normal distribution. Therefore, we need to talk about under what
11:07
condition we can expect more or less a normal distribution.
11:12
And there is a rule of thumb for that. The rule of thumb is... this is rule of thumb.
11:19
It is not a a theorem. Just people have tried out and found that
11:27
it works. That is, if the probability p — and p is
11:39
a probability of getting a 1 — times times the number of samples
11:55
samples is greater than 10, and and if the the probability of the other one; that means,
12:11
1 minus p (1-p) times the number of samples, that is also greater than 10, then then the
12:32
distribution of the measured p̂ will be approximately
12:45
normal. If it is normal, then we can apply all that
13:00
we have learnt about the normal distribution. That is a major advantage.
13:04
But the caveat is that, that is not applicable to all cases.
13:09
For example, if if the if the... in the in the example that we have taken, in the example
13:18
that you have taken. p was 60 0.6, sorry I will do it right correctly p was 0.6, 1 minus
13:31
p was 0.4, and suppose we take 20 samples. n is equal to 20.
13:43
Then it will become p times 20, which is p into n is equal to... p into n will be 12
14:00
and 1 minus p into n will be 8. So, obviously, this is not bigger than ten
14:15
and therefore, in this collection the normal distribution will not apply.
14:21
So, if you keep on drawing samples of 20s and expect p̂ to be distributed in normal
14:27
distribution, that will not work. You have to take more than 20 samples.
14:32
Okay? Then only the normal distribution will work.
14:36
Before we end, let us quickly do an example. There are... consider the Mendel-type experiment
14:46
in which there are tall plants and and short plants, and you have collected a sample of
15:02
50. And you have counted the number and you have
15:06
found that 33 are are tall. I will write.
15:20
So, your your measured proportion is 33 by 50 is equal to 0.66.
15:41
The question is, can you state that the actual proportion out there lies in the range 0.64
15:56
to 0.68? Can you say...?
15:59
So, actual p lies in this range? This is the problem.
16:07
Okay? So, how do we attack this problem?
16:11
We know, the the mean will be... we have calculated the mean, sample mean, to be this, and we
16:21
can calculate the sample standard deviations: σ p̂ to be square root of p 1 minus p by
16:35
n. Now, p we do not know.
16:39
Therefore, we substitute by whatever we have measured, which is this.
16:44
So, it comes to be 0.66 times 1 minus 0.66 divided by the number of samples.
16:55
We have taken 50. Okay?
16:59
And that turns out to be 0.067. Okay?
17:06
Now, will this distribution be a normal distribution? Let’s quickly check: p is 0.66.
17:14
So, p into n is 0.66 times 50 is is 33, and 1 minus p times n is equal to 17.
17:29
So, both are bigger than 10. So, normal!
17:33
Okay? Distribution is normal.
17:34
That is good. So, if the distribution is normal, then we
17:42
can we can picture the distribution something like this.
17:56
And we know the mean will be at p, and the standard deviation we have just calculated.
18:04
Okay? The question was the probability of this.
18:09
So, probability of P of the the mean of p is — not p̂, p — is within 0.66 and 0.64
18:30
0.2 is within 0.2 of the mean: this is what we are trying to calculate.
18:44
So, p̂ 0.66 minus 0.2 and plus 0.2. So, our statement is: what is the probability
18:52
that this is true? So, this is again... sorry...
18:56
I will write this p as capital P because it is a probability.
19:05
Probability of again like the like the earlier problems, we will reverse the argument.
19:13
We will say p̂ is within 0.2 of the mean of p, the distance between this and that is
19:27
the same as distance between this and this. So, we have the same argument.
19:31
And then we can... we have to express that as a multiplier of the standard deviation.
19:39
Then we get the value of z. Okay?
19:40
So, the z value z is the multiplier 0.2, zero point...
19:50
sorry 0.2 or 0.02, 0.02 sorry 02 0.02 divided by the this is 0.067, and that turns out to
20:12
be 0.3. z turns out to 0.3.
20:14
So, we are essentially saying that p̂ is within 0.3 standard divisions of the the mean.
20:21
Now if you now consult the z table and find out what is the... suppose 0.3 is somewhere
20:27
here... 0.3, 0.3 would be 0.6 0.3 will be somewhere here may be.
20:38
So, if you find this area if you find this area then you will find that
20:56
the the area 0.6179. So, this area we will we will subtract 0.5
21:18
from it. So, 0.6179 minus 0.5, thereby we get only
21:27
this area times two. That turns out to be 0.2358.
21:39
So, that is the probability of having the actual the the proportion of the two populations
21:52
out there is to be to be in this range, to be in this range is only this much.
21:59
Which means that, I can state with only 23 percent confidence that the population will
22:06
be in this range. With that population would be in this range.
22:10
It is a very low confidence. That immediately tells us that we need to
22:17
change our strategy. We need to do something else in order to increase
22:21
the level of confidence for proportion measurements. I will stop here and continue with the next
22:26
class.
