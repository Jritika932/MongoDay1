```
use human_resource
switched to db human_resource
human_resource> db.employee.insertMany([
...   {
...
...     firstName: 'John',
...     lastName: 'Doe',
...     salary: '25000',
...     department: 'HR',
...     lastCompany: 'X',
...     lastSalary: '10000',
...     overallExp: '2',
...     contactInfo: '1234567890',
...     yearGrad: '2016',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'roh',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   }
... ])
{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId("6347f39f6a9a7fcb06bc0692"),
    '1': ObjectId("6347f39f6a9a7fcb06bc0693"),
    '2': ObjectId("6347f39f6a9a7fcb06bc0694"),
    '3': ObjectId("6347f39f6a9a7fcb06bc0695"),
    '4': ObjectId("6347f39f6a9a7fcb06bc0696"),
    '5': ObjectId("6347f39f6a9a7fcb06bc0697"),
    '6': ObjectId("6347f39f6a9a7fcb06bc0698"),
    '7': ObjectId("6347f39f6a9a7fcb06bc0699"),
    '8': ObjectId("6347f39f6a9a7fcb06bc069a"),
    '9': ObjectId("6347f39f6a9a7fcb06bc069b"),
    '10': ObjectId("6347f39f6a9a7fcb06bc069c"),
    '11': ObjectId("6347f39f6a9a7fcb06bc069d"),
    '12': ObjectId("6347f39f6a9a7fcb06bc069e")
  }
}
human_resource> db.employee.find().pretty()
[
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0692"),
    firstName: 'John',
    lastName: 'Doe',
    salary: '25000',
    department: 'HR',
    lastCompany: 'X',
    lastSalary: '10000',
    overallExp: '2',
    contactInfo: '1234567890',
    yearGrad: '2016',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0693"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0694"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0695"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0696"),
    firstName: 'Jame',
    lastName: 'roh',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0697"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0698"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc0699"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc069a"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc069b"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc069c"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc069d"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6347f39f6a9a7fcb06bc069e"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  }
]
```