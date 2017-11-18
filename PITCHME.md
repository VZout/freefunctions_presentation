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

@[11-15]
```cpp
class WebBrowser {
public:
	void ClearCache();
	void ClearHistory();
	void RemoveCookies();

private:
	// ...
};

void ClearEverything() {
	ClearCache();
	ClearHistory();
	RemoveCookies();
}
```

---

@title[Step 2. Git-Commit]

### <span class="gold">STEP 2. GIT-COMMIT</span>
<br>

```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```

@[1](Add your PITCHME.md slideshow content file.)
@[2](Commit PITCHME.md to your local repo.)
@[3](Push PITCHME.md to your public repo and you're done!)
@[5](Supports GitHub, GitLab, Bitbucket, GitBucket, Gitea, and Gogs.)

---

@title[Step 3. Done!]

### <span class="gold">STEP 3. GET THE WORD OUT!</span>
<br>
![GitPitch Slideshow URLs](assets/images/gp-slideshow-urls.png)
<br>
<br>
#### Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---

@title[Slide Rich]

### <span class="gold">Slide Rich</span>

#### Code Presenting for Blocks, Files, and GISTs
#### Image, Video, Chart, and Math Slides
#### Multiple Themes with Easy Customization
<br>
#### <span class="gold">Plus collaboration is built-in...</span>
#### Your Slideshow is Part of Your Project
#### Under Git Version Control within Your Git Repo

---

@title[Feature Rich]

### <span class="gold">Feature Rich</span>

#### Present Online or Offline
#### With Speaker Notes Support
#### Print Presentation as PDF
#### Auto-Generated Table-of-Contents
#### Share Presentation on Twitter or LinkedIn

---

### Go for it.
### Just add <span class="gold">PITCHME.md</span> ;)
<br>
[Click here to learn more...](https://github.com/gitpitch/gitpitch/wiki)
