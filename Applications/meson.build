nntr_app_resdir = nntrainer_resdir / 'app'
run_command('mkdir', '-p', nntr_app_resdir)

subdir('utils/jni')
subdir('KNN/jni')
subdir('LogisticRegression/jni')
if enable_ccapi
  subdir('MNIST/jni')
endif
subdir('VGG/jni')
subdir('Resnet/jni')
subdir('ReinforcementLearning/DeepQ/jni')
subdir('TransferLearning/CIFAR_Classification/jni')
if enable_capi
  subdir('TransferLearning/Draw_Classification/jni')
endif
subdir('Custom')
subdir('ProductRatings/jni')

if get_option('enable-tflite-backbone')
  subdir('SimpleShot')
endif

