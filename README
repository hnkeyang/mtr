## WHY DID YOU FORK MTR?

  I wanted JSON output and I wanted all captured performance fields as 
well as IP, Hostname and ASN (if available) normalized into their own
JSON fields and in a single object.  Neither the CSV or XML output do 
this for you.  I also changed the default to --without-gtk.

## EXAMPLE HOP
{
      "hop": 12,
      "ipaddr": "8.8.8.8",
      "host": "google-public-dns-a.google.com",
      "asn": "AS15169",
      "drop": 0,
      "received": 5,
      "geomean": 4.7,
      "jitter": 0.9,
      "jitteravg": 0.7,
      "jittermax": 1.7,
      "jitterint": 3.4,
      "losspercent": 0,
      "sent": 5,
      "last": 4.2,
      "avg": 4.8,
      "best": 4.2,
      "worst": 5.9,
      "stddev": 0.5
}

## INSTALLING

It should first call the "configure" script and then run "make" again
with the makefile that "configure" just generated. 

If you're building from the git repository, you'll need to run:
    ./bootstrap.sh && ./configure && make
After compiling, install:
	make install

  

