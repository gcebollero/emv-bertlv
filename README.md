A library for deciphering [BER TLV](http://en.wikipedia.org/wiki/X.690#BER_encoding) data used in [EMV](http://en.wikipedia.org/wiki/EMV) (chip card transactions).

Dependency Information:

        <dependency>
            <groupId>io.github.binaryfoo</groupId>
            <artifactId>emv-bertlv</artifactId>
            <version>0.1.1</version>
        </dependency>
        
In [Maven Central](https://repo1.maven.org/maven2/io/github/binaryfoo/emv-bertlv/).        

Used in a little [tool](http://tvr-decoder.appspot.com/t/home) hosted on Google's AppEngine.

The tests provide some idea of what kind of data this code can decipher. The [EMVCo](http://www.emvco.com/specifications.aspx) website has the full (1000+ page) specs. Add to that the Visa, Mastercard and Amex documents.

To get started decoding call decode() on [RootDecoder](https://github.com/binaryfoo/emv-bertlv/blob/master/src/main/java/io/github/binaryfoo/RootDecoder.java).