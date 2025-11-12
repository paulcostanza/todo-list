A **package** is a collection of Go source files that reside in the same directory and have the same package declaration at the top. 

```
cmd/
|- main.go

handlers/
|- handler.go

api/
|- api.go
```

Placing all these packages together creates a **module**. 

---

Keep an eye between <code>fmt.Println</code> & <code>fmt.Printf</code>

---

### Go Fiber

An express-inspired web framework written in Go. Fiber is a Go web framework built on top of the fastest HTTP engine for Go -&gt; Fasthttp

---