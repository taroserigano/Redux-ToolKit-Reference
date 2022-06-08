# Redux-ToolKit-Reference


REDUX TOOL KIT 

1. Create "store" in store.js
   -store stores alll the Reducers 

2. Add store in Provider from react-redux
	-makes it available from evverywhere
		ex. import { addFoodToCustomer } from "../feature/customerSlice";

 <button
            onClick={() => {
              dispatch(
                addFoodToCustomer({
                  id,
                  food: customerFoodInput,
                })
              );
            }}
          >


3. 
