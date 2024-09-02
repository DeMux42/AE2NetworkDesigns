# Draw.io Custom Shape Codes

**Links:**

- [Draw.io website](https://www.drawio.com/)  
- [Draw.io custom shapes documentation](https://www.drawio.com/doc/faq/shape-complex-create-edit)  

---

## How to Import Custom Shapes

To import these shapes into draw.io:

1. Go to **Arrange** -> **Insert** -> **Shape**
2. Paste the code provided in each section below.

---

### Contribution Note

These custom shapes are just a starting point and are quite basic. If you have ideas for refining these shapes or if you can add missing AE2 components, **contributions are highly encouraged!** 

- **How to Contribute**: Fork this repository, make your changes, and submit a pull request.
- **What We're Looking For**:
  - Enhancements/coloring to the existing shapes.
  - Shapes for any other AE2 or third-party components

I will review all contributions and, if they meet the quality standards, I'll merge them into the main branch. Your work will be credited, and the default template these shapes are used in will be updated accordingly.

Thank you for helping improve this project!

---

## Shapes

### Importer

```json
<shape h="40" w="60" aspect="fixed" strokewidth="inherit">
  <connections>
    <constraint x="0.5" y="1"/>
  </connections>
  <background>
     <path>
      <move x="0" y="0"/>
      <line x="60" y="0"/>
      <line x="60" y="10"/>
      <line x="50" y="10"/>
      <line x="50" y="20"/>
      <line x="40" y="20"/>
      <line x="40" y="30"/>
      <line x="40" y="40"/>
      <line x="20" y="40"/>
      <line x="20" y="30"/>
      <line x="20" y="20"/>
      <line x="10" y="20"/>
      <line x="10" y="10"/>
      <line x="0" y="10"/>
      <line x="0" y="0"/>
      <close/>
    </path>
  </background>
  <foreground>
    <fillstroke />
    <path>
      <move x="40" y="30"/>
      <line x="20" y="30"/>
    </path>
    <stroke />
  </foreground>
</shape>
```

---

### Exporter

```json
<shape h="40" w="60" aspect="fixed" strokewidth="inherit">
  <connections>
    <constraint x="0.5" y="1"/>
  </connections>
  <background>
     <path>
      <move x="20" y="0"/>
      <line x="40" y="0"/>
      <line x="40" y="10"/>
      <line x="50" y="10"/>
      <line x="50" y="20"/>
      <line x="60" y="20"/>
      <line x="60" y="30"/>
      <line x="40" y="30"/>
      <line x="40" y="40"/>
      <line x="20" y="40"/>
      <line x="20" y="30"/>
      <line x="0" y="30"/>
      <line x="0" y="20"/>
      <line x="10" y="20"/>
      <line x="10" y="10"/>
      <line x="20" y="10"/>
      <line x="20" y="0"/>
      <close/>
    </path>
  </background>
  <foreground>
    <fillstroke />
    <path>
      <move x="40" y="30"/>
      <line x="20" y="30"/>
    </path>
    <stroke />
  </foreground>
</shape>
```

---

### Interface

```json
<shape h="30" w="60" aspect="fixed" strokewidth="inherit">
  <connections>
    <constraint x="0.5" y="1"/>
  </connections>
  <background>
     <path>
      <move x="0" y="0"/>
      <line x="60" y="0"/>
      <line x="60" y="20"/>
      <line x="40" y="20"/>
      <line x="40" y="30"/>
      <line x="20" y="30"/>
      <line x="20" y="20"/>
      <line x="0" y="20"/>
      <line x="0" y="0"/>
      <close/>
    </path>
  </background>
  <foreground>
    <fillstroke />
    <path>
      <move x="40" y="20"/>
      <line x="20" y="20"/>
    </path>
    <stroke />
  </foreground>
</shape>
```

---

### Storage Bus

```json
<shape h="40" w="80" aspect="fixed" strokewidth="inherit">
  <connections>
    <constraint x="0.5" y="1"/>
  </connections>
  <background>
     <path>
      <move x="0" y="10"/>
      <line x="80" y="10"/>
      <line x="60" y="30"/>
      <line x="50" y="30"/>
      <line x="50" y="40"/>
      <line x="30" y="40"/>
      <line x="30" y="30"/>
      <line x="20" y="30"/>
      <line x="0" y="10"/>
      <close/>
    </path>
  </background>
  <foreground>
    <fillstroke />
    <path>
      <move x="50" y="30"/>
      <line x="30" y="30"/>
    </path>
    <stroke />
    <fillstroke/>
    <strokecolor color="#33ff33"/>
    <path>
      <move x="10" y="10"/>
      <line x="15" y="0"/>
      <line x="20" y="10"/>
      <line x="25" y="0"/>
      <line x="30" y="10"/>
      <line x="35" y="0"/>
      <line x="40" y="10"/>
      <line x="45" y="0"/>
      <line x="50" y="10"/>
      <line x="55" y="0"/>
      <line x="60" y="10"/>
      <line x="65" y="0"/>
      <line x="70" y="10"/>
    </path>
    <stroke />
  </foreground>
</shape>
```

---

### ME P2P

```json
<shape h="30" w="60" aspect="fixed" strokewidth="inherit">
  <connections>
    <constraint x="0.5" y="0"/>
    <constraint x="0.5" y="1"/>
  </connections>
  <background>
     <path>
      <move x="10" y="0"/>
      <line x="50" y="0"/>
      <line x="50" y="5"/>
      <line x="60" y="5"/>
      <line x="60" y="20"/>
      <line x="40" y="20"/>
      <line x="40" y="30"/>
      <line x="20" y="30"/>
      <line x="20" y="20"/>
      <line x="0" y="20"/>
      <line x="0" y="5"/>
      <line x="10" y="5"/>
      <close/>
    </path>
  </background>
  <foreground>
    <fillstroke />
    <path>
      <move x="40" y="20"/>
      <line x="20" y="20"/>
    </path>
    <stroke />
  </foreground>
</shape>
```
