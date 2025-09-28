# Data Model

## User
- `Id` (string, primary key)
- `Email` (string)
- `Name` (string)

## Account
- `Id` (string, primary key)
- `UserId` (string, foreign key to User)
- `Name` (string)
- `Bank` (string)
- `AccountNumber` (string)

## Transaction
- `Id` (string, primary key)
- `AccountId` (string, foreign key to Account)
- `Date` (datetime)
- `Description` (string)
- `Amount` (decimal)
- `CategoryId` (string, foreign key to Category)

## Category
- `Id` (string, primary key)
- `UserId` (string, foreign key to User)
- `Name` (string)

## Attachment
- `Id` (string, primary key)
- `TransactionId` (string, foreign key to Transaction)
- `FileName` (string)
- `Url` (string)
