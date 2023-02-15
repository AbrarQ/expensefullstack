
const Sequelize = require ('sequelize');

const sequelizedb  = require('../util/database');



const expensesModel = sequelizedb.define('expenses',{
  id : { 
    type : Sequelize.INTEGER, 
    autoIncrement : true,
    allowNull : false,
    primaryKey : true,
  },

  amount : { 
    type : Sequelize.INTEGER, 
 
  },

  description : { 
    type : Sequelize.INTEGER, 
    
  },
  category : { 
    type : Sequelize.STRING, 
    
  },
})

module.exports = expensesModel;