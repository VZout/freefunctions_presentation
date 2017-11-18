@title[Introduction]

# Free Your Functions!
<span class="primary"><strong>Viktor Zoutman</strong></span>, November 20 2017

---

@title[Preface]

## Klaus Iglberger
#### Meeting C++, November 10 2017

---

@title[Good stuff]

- Encapsulation
- Abstraction / Polymorphism |
- Cohesion |
- Flexibility / Extensibility |
- Reuse / Generality |
- Testability |
- Performance |

---

@title[SOLID]

### SOLID

- **S**ingle **R**esponsibility **P**rinciple
- **O**pen-**C**losed **P**rinciple
- **L**iskov **S**ubstitution **P**rinciple
- **I**nterface **S**egregation **P**rinciple
- **D**ependency **I**nversion **P**rinciple

---

@title[Encapsulation Title]

### Encapsulation

---

@title[WebBrowser Code Example]

```cpp
class WebBrowser {
public:
	void ClearCache();
	void ClearHistory();
	void RemoveCookies();

	void ClearEverything() {
		ClearCache();
		ClearHistory();
		RemoveCookies();
	}
private:
	// ...
};
```
---

@title[Intermission]

![](https://www.nautilusplus.com/content/uploads/2016/08/Pexel_junk-food.jpeg)
![](https://www.nautilusplus.com/content/uploads/2016/08/Pexel_junk-food.jpeg)

