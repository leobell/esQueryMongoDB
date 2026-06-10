# esQueryMongoDB
Esercizi query

1. { isActive: true } 51
2. { age: { $gt: 26 } } 54
3. {age : {$gt:26,$lte:30}} 19
4. {$or:[{eyeColor:{$regex:"brown"}},{eyeColor:{$regex:"blue"}}]} 66
5. {eyeColor:{$not:{$regex:"green"}}} 66
6. {$and:[{eyeColor:{$not:{$regex:"blue"}}},{eyeColor:{$not:{$regex:"green"}}}]} 35
7. { company: {$regex:"FITCORE"}} {email:1,_id:0} 1
