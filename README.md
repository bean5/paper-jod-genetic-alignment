# Alignments Across Multiple Imitation Classes: Using Machine Learning Produce More Accurate Textual

Whitepaper on application of genetic alignment on religious discourses. Base corpus: LDS Journal of Discourses comprised of hundreds of religious discourses.

## Dependencies

- docker
- docker-compose

## Build Instructions

```sh
docker-compose run proposal
docker-compose run final
```

The first time you run the command it will need to build the latex base image which can take a long time.

## To Do

- [ ] Use a common base image to accelerate first-time PDF generation
