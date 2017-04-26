<p align="center">
  <img src="https://raw.githubusercontent.com/siddharthkp/perfbench/master/logo.png" height="200px"/>
  <br><br>
  <b>Performance benchmarks for websites</b>
  <br>
</p>

&nbsp;

[![Build Status](https://travis-ci.org/siddharthkp/reaqt.svg?branch=master)](https://travis-ci.org/siddharthkp/perfbench)

&nbsp;

#### minimal setup
```
npm install perfbench --save
```


#### use with CI (powered by lighthouse)

Add this line in your `.travis.yml`

```yaml
scripts:
  - perfbench https://example.com
```

or `package.json`

```json
"scripts": {
  "test": "perfbench https://example.com"
}
```

&nbsp;

#### metrics measured

- First meaningful paint (1600 ms threshold)
- Speed index metric (1250)
- Time to interactive (2500 ms)
- Total byte weight (1600 Kb)

&nbsp;

#### test conditions

- Network: Regular 3G (750 Kbps)
- Device emulation: Nexus 5X
- CPU: 5x slowdown

&nbsp;

#### like it?

:star: this repo

&nbsp;

#### todo

- only warn
- custom threshold

&nbsp;

#### license

MIT © [siddharthkp](https://github.com/siddharthkp)
