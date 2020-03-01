UFUNCTION(BlueprintCallable, category = "Default")
        UPropertys* createproperty(FString name, UObject &targets, UObject &proertyobjects, TArray<UPropertys> &childproertys)
    {
            return new UPropertys(name, &targets, &proertyobjects, &childproertys);
    }

    Upropertys(UObject *l)
    {
        target = l;
    }
    //UFUNCTION(BlueprintCallable, category = "Default")
    ///*    Upropertys* createproperty(FString name, UObject &targets, UObject &proertyobjects, TArray<Upropertys> &childproertys)
    //{
    //    return new Upropertys(name, &targets, &proertyobjects, &childproertys)
    //}*/
    
    //    Upropertys* createOne(UObject& ob)
    //{
    //    return new UPropertys(&ob);
    //}
        /*int* createproperty()
    {
        int a = 7;
        return &a;
    }
