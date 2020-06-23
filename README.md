# JS Katas - Fire Flower

Work in progress. Nothing to see here.

Resolve every Kata in its own file, following its description bellow.

Launch the unit tests in order to check the correct solution of the Katas.

The solutions must be uploaded to a public github/gitlab repository.

## How to test the code

This project uses `mocha` for testing and `babel` to use ES Modules in the spec files.

Run `npm install` to install all the project dependencies.\
Run `npm test` to check all the test files.\
Run `npm run test1` to check only the tests with the #kata-1 `describe` section, i.e. kata-1.spec.js file.\
Run `npm run test2` to check only the tests with the #kata-2 `describe` section, i.e. kata-2.spec.js file.\
Run `npm run test3` to check only the tests with the #kata-3 `describe` section, i.e. kata-3.spec.js file.

### Kata 1

**Objectives:** time complexity.

Given a collection of distinct integers, return all possible permutations.

Example:

    Input: [1,2,3]
    Output:
    [
        [1,2,3],
        [1,3,2],
        [2,1,3],
        [2,3,1],
        [3,1,2],
        [3,2,1]
    ]

### Kata 2

Labyrinth

    const life = 1;
    const enemy = 2;
    const treasure = 3;
    const baby = 4;
    const bowie = 5;

    const labyrinth = {
        start: {
            left: {
                left: 0,
                right: {
                    left: 5,
                    right: {
                        left: 1,
                        right: 2,
                    },
                },
            },
            right: {
                left: {
                    left: {
                        left: 2,
                        right: 1,
                    },
                    right: {
                        left: 0,
                        right: {
                            left: 4,
                            right: 0,
                        },
                    },
                },
                right: {
                    left: {
                        left: 3,
                        right: 0,
                    },
                    right: 0,
                },
            },
        }
    }
