# Rust Learning Resources
A list of my recommended resources for learning Rust, in addition with a learning path. Note that this is not a listing of all available learning resources for Rust across a variety of different fields and topics. As stated, it is what I recommend to use whilst learning Rust.

# Table of Contents

- [Learning Path](#learning-path)
- [Additional Resources](#additional-resources)

# Learning Path

1. [The Rust Programming Language Book](https://doc.rust-lang.org/stable/book/)
- **NOTES:**
  - This book assumes you have some prior programming knowledge and experience
  - Reading this book is not a recommendation. It is a requirement in my opinion. It is an extremely informative introduction to the language and will help you start off smoothly.
  - Follow along with the code and write the projects that are part of the book.
2. [Rustlings](https://github.com/rust-lang/rustlings)
- **NOTES:**
  - Rustlings is a good way to get yourself dirty writing some Rust code. It is a collection of exercises to help you get acclimated and used to the semantics of the language.
  - Totally optional, but it will help.
3. [Rust By Example](https://doc.rust-lang.org/rust-by-example/)
- **NOTES:**
  - This book provides you with Rust code examples along with explanations about what is going on in the code. It is a nice guided experience to learning Rust, similar to the projects presented in the Rust Programming Language book.
  - Totally optional, but it will help.
4. [The Rust Reference](https://doc.rust-lang.org/reference/introduction.html)
- **NOTES:**
  - This book will give you a good overview about a variety of language constructs in Rust, some of the intricacies of the language, and some other things you might see out in the wild.
  - Recommended
5. Start writing some Rust code. Figure out a project that aligns with your interests and start writing it in Rust. Some easy programs to make as a Rust beginner are programs that take user input, CLI applications, and basic web APIs. You should have enough knowledge by this point to write said projects.
6. [async/.await Book](https://rust-lang.github.io/async-book/01_getting_started/01_chapter.html)
- **NOTES:**
  - By this point, you will have likely encountered or heard about `async` and `.await` and other concurrency related topics in Rust. This is a good point to start learning about how asynchronous programming works in Rust.
  - Highly recommended 
7. [Crust of Rust series by Jon Gjengset](https://youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa)
- **NOTES:**
  - This series is an excellent overview into the more "intermediate" parts of Rust, You will learn about many of the deeper parts and/or more niche parts of Rust like interior mutability (introduced in the Rust book), subtyping and variance, atomics, etc. By the end of the series, you will know much more about Rust and how things work.
  - Highly recommended
8. [Rust for Rustacenas by Jon Gjengset](https://www.amazon.com/Rust-Rustaceans-Programming-Experienced-Developers-ebook/dp/B0957SWKBS)
- **NOTES:**
  - This book is an incredible compliment to the Crust of Rust series. It introduces some other topics that have not yet been covered in the Crust of Rust series.
  - Highly recommended
9. [The Rustonomicon](https://doc.rust-lang.org/stable/nomicon/)
- **NOTES:**
  - By this point, you will have decent experience with Rust. But, you might be wondering about `unsafe` Rust and the deeper, darker parts of the language. This book will tell you all about those topics. It also explains why `unsafe` Rust exists and how it is supposed to interact with safe and other unsafe Rust code. 
  - Some topics in this book were covered in Crust of Rust.
  - Reading this book is not a recommendation. It is a requirement in my opinion.
  
# Additional Resources

These resources can act as references for when you need assistances with other sections of the Rust language and ecosystem.

1. [The Cargo Book](https://doc.rust-lang.org/cargo/)
2. [The Rustup Book](https://rust-lang.github.io/rustup/)
3. [The Rustc Book](https://doc.rust-lang.org/rustc/what-is-rustc.html)
4. [Rust Cheat Sheet](https://cheats.rs)
