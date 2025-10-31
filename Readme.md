# To run the xblock run this in terminal

./setup_env.sh && source xblock-env/bin/activate && python xblock-sdk/manage.py runserver 

# To build the react based frontend, run the following in another terminal
cd drawing-xblock-react/drawing/frontend/ && npm install --legacy-peer-deps && npm run watch

