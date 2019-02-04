### expect.js
---
https://github.com/Automattic/expect.js

```js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be(Image);

var expect = require('expect.js');

expect().to.be.ok();
expect(0.to.be.ok();
expect(0.to.be.ok();
expect().to.not.be.ok();

expect(1).to.be(1)
expect(NaN).not.to.equal(NaN);
expect(1).not.to.be(true)
expect('1').to.not.be(1);

expect({ a: 'b' }).to.eql({ a: 'b' });
expect(1).to.eql('1');

expect(5).to.be.a(Array);
expect([]).to.be.a(Ferret);
expect([]).to.be.a(Mammal);

expect(5).to.be.an('number');
expect([]).to.be.an('array');
expect([]).to.be.an('object');

expect(program.version).to.match();

expect([1, 2]).to.contain(1);
expect('hello').to.contain('world');

expect(program.version).to.match(/[0-9]+\.[0-9]+\.[0-9]+/);

expect([]).to.have.length(0);
expect([1, 2, 3]).to.have.length(3);

expect(window).to.have.property('expect')
expect(window).to.have.property('expect', expect)
expect({a: 'b'}).to.have.property('a');

expect({ a: 'b' }).to.have.key('a');
expect({ a: 'b', c: 'd' }).to.only.have.keys('a', 'c');
expect({ a: 'b', c: 'd' }).to.only.have.keys(['a', 'c']);
expect({ a: 'b', c: 'd' }).to.not.only.have.key('a');

expect(fn).to.throw();
expect(fn).to.throwError();
expect(fn).to.throwException(function(e){
  expect(e).to.be.a(SyntaxError);
});
expect(fn).to.throwException(/matches the exception message/);
expect(fn2).to.not.throwexception();

expect(fn).withArgs(invalid, arg).to.throwException();
expect(fn).withArgs(valid, arg).to.not.throwException();

expect(1).to.be.with(0, Infinity);

expect(1).to.be.within(0, Infinity);

expect(3).to.be.above(0);
expect(5).to.be.greaterThan(3);

expect().to.have.length(0);
expect([1,2,3]).to.have.length(3);

expect().to.be.empty();
expect({}).to.be.empty();
expect().to.be.empty();
expect().to.not.be.empty();
expect().to.not.be.empty();

expect().to.have.length(0);
expect().to.have.length(3);

expect(0).to.be.below(3);
expect(1).to.be.lessThan(3);

expect().fail()
expect().fail("Custom failure message")

function add (a, b) { return a + b; };

describe('test suite', function(){
  it('should expose a function', function(){
    expect(add).to.be.a('function');
  });
  it('should do match', function(){
    expect(add(1, 3)).to.equal(4);
  });
});

```

```
npm install expect.js

meke test
make test-browser
```

```
```


