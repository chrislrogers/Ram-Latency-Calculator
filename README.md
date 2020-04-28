# Ram Latency Calculator

View live [here](https://chrislrogers.github.io/Ram-Latency-Calculator/ "Live Version on GitHub Pages")

# How the calculator works:

To figure out the latency of RAM in nanoseconds we need to know the CAS Latency (CL) and the Clock Speed (in Mhz) of our RAM. When we know these we can use this formula to work out our nanosecond time:

(CL/Clock Speed) * 2000

So for example if we have a Clock Speed of 3600Mhz and a CAS Latency of 18 then we can do the following:

(18/3600) * 2000 = 10

The lower the time in nanoseconds the faster the RAM is.

# Where do I find this info?

These values will typically be written on a label adhered to your RAM or on the OEM packaging/website. For an existing system you can find the values in your BIOS. Your Clock Speed will be the value given in Mhz e.g. 3600Mhz. To find the CAS Latency we take the first number out of the timings which may be displayed as 4 numbers between hyphens e.g. "18-19-19-39" where our CAS Latency is CL18 or it may just show the CAS Latency on the packaging e.g. "CL19"

![alt text](https://chrislrogers.github.io/Ram-Latency-Calculator/label.png "RAM Label Example")
